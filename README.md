# Telco Customer Churn Prediction

Predicting which telecom customers are likely to cancel their service using machine learning.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

## About

One of my first data science projects. I worked with a Kaggle dataset of 7,043 telecom customers to figure out what makes people cancel their service and build a model that can predict it.

## Notebooks

| | Notebook | Description |
|--|----------|-------------|
| P1 | `01_Exploratory_Data_Analysis.ipynb` | Data cleaning, feature engineering and EDA |
| P2 | `02_Modeling.ipynb` | Model training, evaluation and feature importance |

## What I Did

**P1 EDA & Preprocessing**

Cleaned the dataset, handled hidden missing values, engineered new features like `tenure_segment`, `total_services` and `avg_monthly_charges`, and explored how each variable relates to churn through univariate and multivariate analysis.

**P2 Modeling**

Trained and compared three classification models: Logistic Regression as a baseline, Random Forest, and XGBoost. Given the class imbalance (26.5% churn rate), I used F1-score and Recall as the main evaluation metrics.

## Key Findings

Contract type is the strongest predictor of churn. Month-to-month customers churn at 43% while two-year contract customers churn at only 3%, that's a big difference.

The first year is the critical retention window. Most customers who leave do so within their first 10 months. If they make it past that point they tend to stay.

Fiber optic customers churn at 42%, nearly double the DSL rate. This points to pricing or service quality issues in that segment.

Electronic check users churn at 3x the rate of customers on automatic payments. Automatic payments create friction to cancel, electronic check does not.

## Dataset

[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

7,043 customers, 21 features, binary classification target.
