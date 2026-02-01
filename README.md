# House Price Prediction with Machine Learning

End-to-end machine learning regression project for predicting house prices using Python and scikit-learn.  
The project demonstrates a full data science workflow including data exploration, feature engineering, pipelines, cross-validation, model comparison, and interpretation.

This repository is designed as a **portfolio project** for data science / machine learning roles.

---

## Project Overview

Accurately estimating house prices is important for real estate platforms, investors, and buyers.  
The goal of this project is to build and evaluate regression models that predict residential property prices based on structural and location-related features.

The focus is not only on performance, but also on reproducibility, proper ML practices (no data leakage), interpretability, clean project structure

---

## Approach

The project follows these steps:

- Data loading and inspection  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Train / test split  
- Preprocessing with pipelines  
- Model training  
- Cross-validation  
- Model comparison  
- Evaluation using MAE, RMSE and R²  
- Residual analysis and feature importance  

Models evaluated:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Random Forest Regressor  

---

## Dataset

The dataset contains information about residential properties, including:

- Size of the house  
- Age of the property  
- Distance to city center  
- Target variable: price  

The dataset is stored in the `data/` folder and loaded using relative paths to ensure reproducibility.

---