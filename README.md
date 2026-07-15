# Telco Customer Churn Prediction

Predicting which telecom customers are likely to cancel their service using machine learning.

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)

## About

One of my first end-to-end data science projects. I worked with a Kaggle dataset of 7,043 telecom customers to figure out what makes people cancel their service and build a model that can predict it.

## Notebooks

| | Notebook | Status |
|--|----------|--------|
| P1 | EDA & Preprocessing | ✅ Done |
| P2 | Modeling | 🔄 Coming soon |

## Main Takeaways from the Analysis

Contract type turned out to be the biggest factor. Month-to-month customers churn at 43% while two-year contract customers barely churn at all (3%). Fiber optic customers also leave at a surprisingly high rate (42%), and electronic check users churn 3x more than people on automatic payments.

## Models (P2)

Logistic Regression, Random Forest and XGBoost. Using F1-score and Recall as main metrics since only 26.5% of customers churned.

## Dataset

[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Install

pip install pandas numpy seaborn matplotlib scikit-learn xgboost kagglehub
