# nba-compensation-prediction
Predicting NBA player market compensation using R, tidymodels, and regression pipelines.

# Predictive Modeling of NBA Athlete Compensation

An end-to-end machine learning and regression analysis in R forecasting NBA player compensation based on multi-metric box score performance.

## Project Overview
- **Objective**: Identify key performance drivers of NBA athlete salary allocations and evaluate predictive accuracy across multiple machine learning architectures.
- **Data Scope**: Box-score metrics and contract records spanning 50+ athletic and statistical variables.
- **Key Challenge**: Resolving high multicollinearity among traditional and advanced box-score metrics.

## Methodology & Tools
- **Environment**: R (`tidymodels`, `tidyverse`, `ggplot2`)
- **Workflow**: Exploratory data analysis, feature selection/engineering, 5-fold cross-validation.
- **Models Benchmarked**: 
  - Regularized Regression (Lasso / Elastic Net)
  - Decision Trees
  - Random Forest

## Key Insights
- Penalized redundant collinear metrics to isolate primary performance indicators tied to contract valuations.
- Benchmarked predictive performance across models to determine optimal out-of-sample error reduction.

## Deliverables & Source Files
- `index.html` (or `NBA_Analysis.html`): Complete interactive technical report with data visualizations and diagnostic outputs.
- `*.Rmd`: Reproducible R Markdown analysis pipeline.
