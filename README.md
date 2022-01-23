# Advanced-Regression-Techniques-for-Real-Estate-Prices
Predict real estate prices and practice feature engineering, RFs, GBs, models ensembling.

## Data
Boston Housing dataset

https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Steps
1) **EDA**, complete missing values, deal outliers
2) **Feature engineering**
3) **Variables dependencies** (ANOVA, Point Biserial Correlation, Cramers V, Chi-2 test, Pearson & Spearman corr)
4) **Check regression assumption**s (residuals normality test, residuals homoscedasticity/heteroskedasticity test, autocorrelation of residuals test, multicollinearity)
5) **Feature selection** with OLS (backward Selection, forward selection, recursive feature elimination)
6) Define models (Lasso L1, Ridge L2, ElasticNet, LinReg, SVR, XGB Regressor, LightGBM Regressor, GB Regressor) and **optimize hyperparameters** (GridSearch, BayesianSearch, Optuna)
7) **Stacking and Voting Regressors**
8) Select models for final prediction - Voting Regressor

Evaluation metric: RMSE
