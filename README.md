# House Price Prediction Using Data Analysis and Machine Learning

## Project Overview
This project focuses on predicting **house sale prices (`SalePrice`)** using historical housing data and multiple property-related features. It demonstrates my understanding of the complete machine learning pipeline, starting from exploratory data analysis and preprocessing, to training, evaluating, and optimizing multiple regression models.

The goal of the project is to build accurate and well-generalized models for **house price prediction** after properly cleaning, transforming, and analyzing the data.

---

## Problem Definition
- **Task Type:** Supervised Machine Learning (Regression)
- **Target Variable:** `SalePrice`
- **Domain:** Real Estate / Housing Market
- **Objective:** Predict house sale prices using property features and compare different regression models to select the best-performing one.

---

## Project Objectives
- Understand housing data through exploratory data analysis (EDA)
- Handle missing values for numerical and categorical features
- Detect and treat outliers that affect house price prediction
- Apply feature transformations to reduce skewness
- Engineer meaningful features related to house age and quality
- Train and compare multiple regression models
- Evaluate models using appropriate regression metrics
- Optimize the final model using hyperparameter tuning

---

## Dataset Description
The project uses two datasets:

- **train.csv**: Used for exploratory data analysis, preprocessing, model training, and evaluation.  
  This dataset includes the target variable `SalePrice`.

- **test.csv**: Used as unseen data to test how the trained model performs on new and real-world–like inputs.  
  This dataset does not contain the target variable and is used only for prediction.

This separation helps simulate a realistic machine learning workflow and ensures that the model is evaluated on data it has not seen during training.


## Workflow Summary

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of `SalePrice`
- Correlation analysis between house features and price
- Visualization of key numerical and categorical features

### 2. Data Preprocessing
- Missing value imputation based on feature type
- Handling categorical variables
- Outlier detection using IQR and Z-score methods
- Log transformation of `SalePrice` to reduce skewness
- Feature engineering (house age, quality-related features)

### 3. Model Training
- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting (XGBoost)

### 4. Model Evaluation
- Comparison using RMSE, MAE, and R² score
- Residual analysis to inspect prediction errors
- Feature importance analysis for tree-based models

### 5. Model Optimization
- Hyperparameter tuning using GridSearchCV
- Final model selection based on performance and generalization

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost

---

## Key Results
- Ensemble models achieved better performance for house price prediction
- Log transformation of `SalePrice` improved model stability
- Feature quality and house size were strong predictors of sale price

---

## What I Learned
- How preprocessing decisions directly affect house price prediction
- The importance of handling skewed target variables in regression
- Differences between linear and ensemble regression models
- How to evaluate regression models using multiple metrics
- How feature engineering improves real-world prediction tasks

---

## Future Improvements
- Additional feature engineering based on domain knowledge
- More advanced cross-validation strategies
- Deployment of the house price prediction model

---

## Author
**Azzam **  
AI & Machine Learning Learner
