# US Home Price Macro Model (Case-Shiller Index)

This repository contains a data science model built as part of the Home.LLC Quantitative Analytics Interview – Stage 1.

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
- `US_Home_Prices_Assignment.ipynb`: Main modeling notebook


## Next Steps
- Introduce lagged features, rolling windows
- Explore regional modeling
- Consider policy shocks and ARIMA-based extensions

