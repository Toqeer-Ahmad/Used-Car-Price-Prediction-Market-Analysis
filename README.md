# Used Car Price Prediction & Market Analysis<br />

## Problem Statement<br />
Accurately estimating used car prices is essential for buyers, sellers, and dealerships.<br />
This project explores vehicle attributes and builds regression models to predict market price based on features such as mileage, engine size, fuel type, and transmission.<br />

## Exploratory Data Analysis<br />
Key Findings:<br />
- Price decreases significantly with increasing mileage.<br />
- Automatic transmission vehicles tend to have higher average prices.<br />
- Newer model years strongly correlate with higher price values.<br />

## Models Implemented<br />
- Linear Regression<br />
- Ridge Regression<br />
- Random Forest Regressor<br />

## Model Performance<br />
| # | Model | RMSE | R² Score |
|---|-------|------|----------|
| 0 | Linear Regression | 2508.120645 | 0.923643 |
| 1 | Ridge Regression	| 2492.504084 | 0.924591 |
| 2 | Random Forest | 1973.917671 | 0.952706 |

## Feature Engineering<br />
- Log transformation applied to skewed variables<br />
- One-hot encoding for categorical features<br />
- Standardization of numerical variables<br />

## Conclusion<br />
Random Forest achieved the best performance, capturing non-linear relationships between vehicle attributes and price. Mileage and model year were the strongest predictors of vehicle value.<br />
