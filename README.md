House Price Predictor

An end-to-end machine learning pipeline predicting house prices using the Ames Housing dataset.

## Models Used
- Ridge Regression
- Gradient Boosting
- XGBoost (best performer)

## Results
| Model | CV RMSE (log) | CV R² |
|---|---|---|
| Ridge Regression | 0.1486 | 0.8449 |
| Gradient Boosting | 0.1317 | 0.8857 |
| XGBoost | 0.1297 | 0.8898 |

## What's Inside
- Full exploratory data analysis (EDA)
- Preprocessing pipeline with imputation and one-hot encoding
- 5-fold cross validation across 3 models
- Feature importance chart
- Actual vs Predicted + Residual plots

## Stack
`pandas` · `scikit-learn` · `xgboost` · `matplotlib` · `seaborn`

## Dataset
[Ames Housing Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

