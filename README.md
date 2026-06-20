# StatStart

An interactive tool for learning statistics by changing inputs and watching the results update.

**Use it now: https://leander-ds.github.io/stat-start/**

## Opening it

Open the live page above in any browser, or download `index.html` and double-click it. It is the whole app in a single file: it runs in any browser, works offline, and needs nothing installed.

## How to use it

1. Pick a method from the tabs along the top. Each tab is its own self-contained example.
2. Drag the sliders on the right (means, spread, sample size, effect size, and similar). Every plot and number updates as you drag.
3. Try a Quick scenario. The preset chips load a ready example in one click, such as a strong overlap with a small sample, or high collinearity.
4. Toggle a violation such as outliers, skew, or unequal variance to see how it changes the test and trips the assumption checks.
5. Read the result panel: the headline statistic, a verdict in ordinary words, and a list of assumptions marked with a check, a warning, or an info icon.
6. Tap any "?" next to a control for a short explanation.

Some tabs (such as Moderation and the regression tabs) have an "Advanced view" box. Leave it off to see just the core result, and turn it on for the extra plots and options once you are comfortable.

## The tabs

Descriptives, Correlation, t-test, Paired t, ANOVA, Contingency, Simple regression, Polynomial, Multiple regression, Moderation, Mediation, Power, and CLT. The examples are framed around work and organizational settings: job satisfaction, engagement, performance, training, and so on.

## The panels below each method

- Statistical output: the result tables in the format a statistics package would print.
- R code: ready to copy and paste, in two versions. One reproduces the exact data you downloaded; the other simulates the same setup from scratch with `set.seed()`.
- Exercise: a short task plus a multiple-choice question to check your understanding.
- Data (CSV): download the current dataset to re-run it anywhere.

## Tutorial

Press the Tutorial button to start a guided tour. Use the arrow keys to move between steps and Esc to leave. Each step sets a tab to a teaching scenario with a one-line explanation, which works well for projecting in class. The tour covers all thirteen tabs.

## Notes

Significance uses an alpha of 0.05 throughout. The t and F distributions are exact, and regression is solved by the normal equations with real standard errors.

Written by Leander De Schutter.
