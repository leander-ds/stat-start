# StatStart

A single page for learning statistics by changing the inputs and watching every plot, number, and verdict update as you go.

**Use it now: https://leander-ds.github.io/stat-start/**

## Opening it

Open the live page above in any browser, or download `index.html` and double-click it. The whole app is one file. It runs in any browser, works offline, and needs nothing installed.

## How to use it

1. Pick a method from the tabs along the top. Each tab is a self-contained example.
2. Drag the sliders (means, spread, sample size, effect size, and the like). Every plot and number updates as you drag.
3. Try a Quick scenario. The preset chips load a ready example in one click, such as a strong overlap with a small sample, or high collinearity.
4. Toggle a violation such as outliers, skew, or unequal variance, and watch how it moves the test and trips the assumption checks.
5. Read the result: the headline statistic, a verdict in plain words, and the assumptions marked with a check, a warning, or an info icon.
6. Tap any “?” next to a control for a short explanation.

## Standard and Full

A Detail level switch sits at the top right, set to Standard by default. Standard keeps each tab to the core result, so it stays uncluttered. Switch to Full and each tab adds more: extra plots and options, a note on effect size versus significance, and a short “if it fails” line under the assumptions that tells you what to use instead. Standard is the cleaner view for a first look or for projecting in class. Full is there when you want the depth.

## What each tab shows you

- **The data plot.** The current sample drawn live, with means, lines, or groups marked.
- **Where the statistic lands under the null.** On the test tabs, a small curve of how the statistic would vary if there were no real effect, with your value marked and the tail beyond it shaded. That shaded tail is the p-value.
- **How is this worked out.** A short, plain explanation of the method, with the formula written out and, on the main tabs, the same formula filled in with the current numbers.
- **The result.** The statistic, the p-value, an effect size, and a one-line verdict.
- **Assumptions.** Each one marked with a check, a warning, or an info icon, and in Full, what to switch to if it fails.
- **Statistical output.** The result tables in the format a statistics package would print.
- **R code.** Ready to copy, in two versions. One reproduces the exact data you downloaded. The other simulates the same setup from scratch with `set.seed()`.
- **Exercise.** A short task plus a multiple-choice question to check understanding.
- **Data (CSV).** Download the current dataset to re-run it anywhere.

## The tabs

Descriptives, Correlation, t-test, Paired t, ANOVA, Contingency, Simple regression, Polynomial, Multiple regression, Moderation, Mediation, Power, and CLT. The examples are framed around work and organizational settings: job satisfaction, engagement, performance, training, and so on.

## Tutorial

Press the Tutorial button for a guided tour. Use the arrow keys to move between steps and Esc to leave. Each step sets a tab to a teaching scenario with a one-line explanation, which works well for projecting in class. The tour covers all thirteen tabs.

## Notes

Significance uses an alpha of 0.05 throughout. The t, F, and chi-square distributions are exact, and regression is solved by the normal equations with real standard errors. Data is generated live and downloadable as CSV, and the R code in each tab reproduces the result.

Leander De Schutter
