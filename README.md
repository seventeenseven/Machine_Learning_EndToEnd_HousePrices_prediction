# End-to-End Machine Learning Project: California Housing Prices

This repository contains a comprehensive notebook demonstrating an end-to-end Machine Learning (ML) workflow for predicting California house prices. The project utilizes various data preprocessing, feature engineering, and model evaluation techniques to provide a structured approach to ML problems.

## Table of Contents
1. **Introduction**
2. **Data Extraction and Loading**
3. **Exploratory Data Analysis (EDA)**
4. **Data Preparation**
5. **Model Selection and Training**
6. **Hyperparameter Tuning**
7. **Model Testing and Evaluation**
8. **Model Persistence**
9. **Bonus Exercise**

## Project Workflow

### 1. Introduction
- Objective: Predict the median house value based on demographic and geographical features.
- Dataset: California Housing Prices dataset from Hands-On ML book by Aurélien Géron.

### 2. Data Extraction and Loading
- Data sourced from a `.tgz` file.
- Loaded into a Pandas DataFrame and explored for structure and distribution.

### 3. Exploratory Data Analysis (EDA)
- Visualized data distributions and geographical trends.
- Analyzed feature correlations to identify key predictors of house prices.

### 4. Data Preparation
- Handled missing values with imputation.
- Encoded categorical variables with `OneHotEncoder`.
- Built a preprocessing pipeline integrating imputation, custom transformations, and scaling.

### 5. Model Selection and Training
- Trained multiple ML models, including:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Evaluated models using RMSE and cross-validation.

### 6. Hyperparameter Tuning
- Fine-tuned Random Forest Regressor using Grid Search.
- Analyzed the best model and identified common sources of error.

### 7. Model Testing and Evaluation
- Tested the best model on the test set.
- Achieved robust performance metrics and insights into predictive accuracy.

### 8. Model Persistence
- Saved the trained model with `joblib` for future use.

## Usage
Clone the repository and open the notebook:
```bash
git clone https://github.com/seventeenseven/california-housing-ml.git
cd california-housing-ml
jupyter notebook
