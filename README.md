# Real Estate Price Prediction Models

This repository contains three machine learning projects to assist a real estate consultancy in making data-driven decisions regarding property investments. The projects focus on predicting housing prices

---

## Project Overview

### Context
Real estate pricing is crucial for developers, agencies, and investors. Traditionally, home appraisals determine property values using an official, unbiased methodology. This repository contains data-driven solutions for:

1. **Predicting the actual sale price of properties.**
2. **Classifying properties as above or below a benchmark value.**

### Dataset
The projects use a dataset from Ames, Iowa, which includes historical housing prices and over 80 features (e.g., area, condition, amenities). These projects demonstrate regression and classification techniques using this data.

---

## Project Contents

### 1. **Classification Models**
- **Notebook:** `classification_housing_prices.ipynb`
- **Objective:** Determine if a property's "true value" is above or below a benchmark price.
- **Key Techniques:**
  - Data preprocessing (handling categorical and numerical features).
  - Feature engineering.
  - Comparison of classification models:
    - Logistic Regression
    - Decision Trees
    - Random Forests
    - Gradient Boosting
  - Model evaluation using metrics such as Accuracy, Precision, Recall, and F1-score.

---

### 2. **Regression Models Without Feature Selection**
- **Notebook:** `01_regression__housing.ipynb`
- **Objective:** Predict the sale price of properties using all available features.
- **Key Techniques:**
  - Data preprocessing (imputation, encoding, scaling).
  - Regression models:
    - Linear Regression
    - Decision Trees
    - Random Forests
    - Gradient Boosting
  - Model evaluation using metrics like MAE, RMSE, and R².
  - Baseline comparisons to Dummy Regressors.

---

### 3. **Regression Models With Feature Selection**
- **Notebook:** `03_regression__housing_with_Feature_selection.ipynb`
- **Objective:** Improve regression model performance using feature selection techniques.
- **Key Techniques:**
  - Variance thresholding to remove low-variance features.
  - Recursive Feature Elimination (RFE).
  - Feature importance-based selection.
  - Improved regression models:
    - Linear Regression
    - Decision Trees
    - Random Forests
    - Gradient Boosting
  - Comparison of model performance before and after feature selection.

---
