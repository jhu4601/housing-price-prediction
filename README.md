# Housing Price Prediction with Random Forest
**Kaggle House Prices: Advanced Regression Techniques**

## Overview
Predicted residential home sale prices using 79 features spanning lot size,
neighborhood, build quality, and more. Iteratively improved a Random Forest
model through feature engineering and missing value handling.

## Approach
- **EDA** to understand distributions across 79 features
- **Missing value handling** for categorical and numeric columns
- **Feature engineering** to extract signal from raw attributes
- **Model:** Random Forest Regressor (100 estimators)
- **Iterative improvement** — compared multiple model versions to reduce RMSE
- **Evaluation metric:** RMSE (Root Mean Squared Error)

## Results
| Model Version | RMSE |
|--------------|------|
| Baseline RF | ~30,000+ |
| Improved RF | 19,677 |

## Tools Used
Python (scikit-learn, pandas, numpy, matplotlib, seaborn)

## Competition
[Kaggle House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
