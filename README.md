# US Home Price Macro Model (Case-Shiller Index)

This repository contains A US Home Price Macro Model

## Objective
Model the impact of macroeconomic factors on the S&P Case-Shiller US Home Price Index over the last 20 years using publicly available data.

## Data Sources
- [S&P Case-Shiller Home Price Index](https://fred.stlouisfed.org/series/CSUSHPISA)
- Mortgage Rate, CPI, S&P 500, etc. from FRED and public government datasets

## Methodology
- Built OLS regression model to predict YoY log changes in home prices
- Performed VIF analysis, residual checks
- Explored nonlinear modeling with XGBoost
- Achieved adjusted R² of 0.698 on the OLS model

## Files
- `notebooks/01_model_building.ipynb`: Main modeling notebook
- `results/model_summary.txt`: Key results summary

## Next Steps
- Introduce lagged features, rolling windows
- Explore regional modeling
- Consider policy shocks and ARIMA-based extensions
