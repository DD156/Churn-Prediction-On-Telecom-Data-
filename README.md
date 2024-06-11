# Churn Prediction on Telecom Data

## Project Overview
This project focuses on predicting customer churn using telecom data. The dataset contains over 100 columns, many of which are highly correlated or unrelated to the target feature. Our analysis covers data cleaning, feature selection, and model comparison to provide a comprehensive approach to churn prediction.

## Table of Contents
1. [Data Analysis](#data-analysis)
2. [Handling Missing Data](#handling-missing-data)
3. [Feature Selection](#feature-selection)
4. [Modeling](#modeling)
5. [Hyperparameter Tuning](#hyperparameter-tuning)
6. [Production Pipeline](#production-pipeline)
7. [Conclusion](#conclusion)

## Data Analysis
- Conducted extensive exploratory data analysis.
- Performed statistical tests such as chi-square tests, correlation tests, and variance tests.
- Identified highly correlated and irrelevant features.

## Handling Missing Data
- Identified categories of missingness: MAR (Missing At Random), MNAR (Missing Not At Random).
- Applied various imputation techniques:
  - Simple imputation (mean, mode, median)
  - KNN imputation, considering distance algorithms
  - MICE imputation leveraging LGBM

## Feature Selection
- Applied different encoding techniques based on data types.
- Used filter-based methods like variance filtering and correlation filtering.
- Implemented wrapper methods such as Recursive Feature Elimination (RFE).
- Utilized feature importance techniques using CatBoost for feature selection.

## Modeling
- Employed several machine learning algorithms:
  - Logistic Regression
  - Decision Tree
  - CatBoost
  - LightGBM (LGBM)
  - XGBoost
- Compared model performances in the prediction phase.

## Hyperparameter Tuning
- Utilized Optuna for hyperparameter tuning through Bayesian optimization.
- Implemented cross-validation techniques to ensure robust model evaluation.

## Production Pipeline
- Built a pipeline to demonstrate feature usage in a production environment.

## Conclusion
- Summarized findings and provided detailed conclusions.
- Offered suggestions for further improvements and future work.

