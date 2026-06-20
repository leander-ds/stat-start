# StatStart

An interactive tool for learning statistics by changing things and watching what happens.

## Open it

Double-click `index.html` — that's the whole app. It runs in any browser, offline, with nothing to install. (Or visit the hosted page if you've put it online.)

## How to use it

1. **Pick a method** from the tabs along the top: Descriptives, Correlation, t-test, ANOVA, Simple regression, Multiple regression, Power, or CLT. Each tab is self-contained.
2. **Drag the sliders** on the right (means, spread, sample size, effect size, …). Every plot and number updates live.
3. **Try a Quick scenario** — the preset chips load a ready-made example (e.g. *strong overlap, small sample*, *heteroscedastic*, *high collinearity*) in one tap.
4. **Toggle a violation** (outliers, skew, unequal variance, …) to see how it breaks the test and trips the assumption checks.
5. **Read the result panel**: the headline statistic, a plain-language verdict, and a ✓ / ! / i list of assumptions.
6. **Tap any “?”** next to a control for a plain-English explanation.

## The panels below each method

- **SPSS-style output** — the same tables you'd see in SPSS.
- **R code** — copy-paste ready, in two versions: one reproduces the exact data you downloaded, the other simulates the same setup from scratch with `set.seed()`.
- **APA write-up** — a results sentence built from the current numbers; press **Copy**.
- **Exercise** — a short task plus a multiple-choice question to check understanding.
- **⬇ Data (CSV)** — download the current dataset to re-run anywhere.

## Presenter mode (for teaching)

Press the presenter button to start a guided tour. Use the **arrow keys** to move between steps and **Esc** to exit. Each step pre-sets a tab to a teaching scenario with a one-line explanation — useful for projecting in a lecture.
