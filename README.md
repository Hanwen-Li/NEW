# Zillow-s-Home-Value-Prediction
## Source of the data: 
https://www.kaggle.com/c/zillow-prize-1
## Overview
This report is to construct a model to predict a home's current market value, and it is a Regression problem. We nned to do some data pre-processing first, following are steps:

- Missing value imputation & Feature selection
- One-hot-encoding for the categorical data and some ordinal features
- Remove outliers
- Log-tansform the feature (if needed)
- Normalize the feature scale before modeling
- Modeling (Random forest, XGBoost, tuning the parameter by RandomizeCV)
- Evaluate each model with MAE
