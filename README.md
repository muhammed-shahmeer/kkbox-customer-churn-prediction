# KKBOX Customer Churn Prediction

> End-to-end customer churn prediction using advanced feature engineering, LightGBM, SHAP explainability, and business intelligence to identify high-risk customers and support data-driven retention strategies.>
> 
## Overview

This project develops an end-to-end machine learning solution for predicting customer churn using the KKBOX subscription dataset. The project combines advanced feature engineering, gradient boosting models, SHAP explainability, and business intelligence to identify high-risk customers and generate actionable retention strategies.

The objective is not only to build an accurate predictive model but also to transform model predictions into business insights that can help reduce customer churn and improve customer lifetime value.

## Dataset

This project uses the KKBOX Customer Churn Prediction dataset from Kaggle.

The project combines information from four primary datasets:
| Dataset              | Description                                                                   |
| -------------------- | ----------------------------------------------------------------------------- |
| **train.csv**        | Target dataset containing customer IDs and churn labels.                      |
| **members.csv**      | Customer demographic information and registration details.                    |
| **transactions.csv** | Subscription plans, payments, renewals, cancellations, and pricing history.   |
| **user_logs.csv**    | Daily music listening activity, including play counts and listening duration. |


These datasets were merged through extensive feature engineering to create a customer-level dataset containing behavioral, subscription, payment, and engagement features for machine learning.

## Problem Statement

Customer churn is one of the biggest challenges for subscription-based businesses.

The goal of this project is to build a machine learning model capable of identifying customers who are most likely to cancel their subscription before churn actually occurs.

The resulting predictions enable businesses to:

- Target retention campaigns efficiently
- Reduce customer acquisition costs
- Increase customer lifetime value
- Improve marketing ROI

## Technologies Used

- Python
- Polars
- Pandas
- Scikit-learn
- LightGBM
- CatBoost
- XGBoost
- Optuna
- SHAP
- Plotly
- Matplotlib

## Project Workflow

Raw Data
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Optimization
      │
      ▼
Model Evaluation
      │
      ▼
Business Intelligence
      │
      ▼
Business Insight
      │
      ▼
Business Recommendations
      │
      ▼
SHAP Explainability
