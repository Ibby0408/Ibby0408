# Hi, I'm Ibrahim (Ibby)

I'm a Statistics and Data Science student at UCLA. I like projects where the question comes first and the model has to earn its place: check the assumptions, justify the transformations, and say plainly what the results do and don't show.

**Tools:** R, Quarto, Python, SQL

## Selected projects

### 1. [West LA Rental Price Model](https://github.com/Ibby0408/west-la-rent-model) (UCLA Stats 101A)
Multiple linear regression on 2,200+ rental listings across 15 ZIP codes near UCLA (R).
- Cleaned data from the RentCast API, with documented decisions (dropped a 31.6%-missing variable, handled collinear lat/long, removed impossible listings).
- Chose a log response using the inverse response plot and Box-Cox, and a square-root predictor using AIC/BIC.
- Checked VIFs, residuals, and Cook's distance. Final model: R² = 0.81.
- **My contribution:** Analysis and model selection.

### 2. [Attention Experiment](https://github.com/Ibby0408/attention-experiment) (UCLA Stats 101B, team project)
Matched-pair randomized experiment: does 30 minutes of TV, versus sitting quietly, change immediate performance on an attention test? 122 participants were paired on baseline scores, then randomized within each pair, and analyzed with a block-adjusted linear model (equivalent to a paired t-test).
- Result: TV was associated with 1.47 more missed items (95% CI -1.15 to 4.08, p = 0.27). Not significant, but the interval includes the prespecified meaningful difference of 4 items, so we reported it as inconclusive rather than "no effect."
- The report also documents a power recalculation (independent to paired design, 226 to 116 participants), protocol deviations, residual diagnostics, and the limits of generalizing beyond the enrolled participants.
- **My contribution:** rationale and abstract; design, allocation, protocol, and power calculation; data audit, deviations, visualization, and descriptive summaries. I was also the member responsible for checking the data, reported results, and analysis file.

### 3. [Global Health Spending](https://github.com/Ibby0408/global-health-spending) (team project)
Country-level health financing and spending, 2000-2023: who pays, what it buys, and how it relates to life expectancy across income groups. Includes quadratic fits (R² = 0.41 for per-capita prevention spending, 0.79 for total spending) and a written discussion of confounding by national income.
- **My contribution:** Finance spending data exploration and visualizations.

### 4. [Short-Form Video Virality](https://github.com/Ibby0408/virality-video-project) (team project, UCLA Art.ificial x DataPath)
Exploratory analysis of about 47,600 short-form videos, plus a rule-based virality scorer for YouTube links.
- **My contribution:** built the scoring algorithm and did the video-duration distribution analysis.

## Contact

ibby@ucla.edu

