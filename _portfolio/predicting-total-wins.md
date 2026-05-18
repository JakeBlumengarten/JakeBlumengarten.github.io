---
title: "College Football Total Wins Prediction Model"
excerpt: "Engineered a season-level linear regression model using historical CFB data to identify elite tier teams statistically."
collection: portfolio
date: 2025-12-12
header:
  teaser: /images/winsmodel.png
---

### Project Overview
Constructed a robust linear regression model spanning over two decades of historical data (2004–2025) to evaluate if elite college football teams can be cleanly isolated and identified via seasonal performance metrics.

![Total Wins Prediction Model](/images/winsmodel.png)

### Technical Execution
* **Data Pipelines:** Automated data ingestion, cleaning, and aggregation in R utilizing the `cfbfastR` API.
* **Feature Selection:** Filtered and optimized statistical predictors through rigorous model tuning, applying **LASSO regression**, **Variance Inflation Factors (VIF)** to eliminate multicollinearity, and **AIC-based backward elimination**.
* **Skills:** Data Analytics, Statistics, R
* **Live App (Prediction Model):** [Interactive Total Wins Predictor](https://jakeblumengarten.shinyapps.io/predict_total_wins/)
* **Live App (Team Report):** [Interactive Team Report](https://jakeblumengarten.shinyapps.io/team_report_random/)