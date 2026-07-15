# Telco Customer Churn Prediction

A machine learning project to predict which telecom customers are likely to cancel their service, and understand why.

## About the Project

This is one of my first data science projects. I picked customer churn because it's a real business problem that actually matters  companies lose a lot of money when customers leave, and being able to predict that in advance is genuinely useful.

The dataset is from Kaggle and covers 7,043 customers from a telecom company, with info on their contracts, services, payment methods, and whether they churned or not.

---

## Project Structure

| Phase | Notebook | Status |
|-------|----------|--------|
| P1 — EDA & Preprocessing | `01_Exploratory_Data_Analysis.ipynb` | ✅ Done |
| P2 — Modeling | `02_Modeling.ipynb` | 🔄 In progress |

---

## What I Found in the Data

A few things stood out during the analysis:

**Contract type is everything.** Month-to-month customers churn at 43%, while two-year contract customers churn at only 3%. That's a 14x difference.

**The first year is critical.** Most customers who leave do so within their first 10 months. If they make it past that, they tend to stick around.

**Fiber optic customers are leaving at 42%.** That's way higher than DSL at 19%, which raises questions about pricing or service quality in that segment.

**Payment method matters more than expected.** Electronic check users churn at 3x the rate of people on automatic payments. Makes sense automatic payments are harder to cancel.

---

## Models (P2 — coming soon)

Planning to train and compare three models:
- Logistic Regression (baseline)
- Random Forest
- XGBoost

Since only 26.5% of customers churned, accuracy alone isn't a great metric here. I'll be focusing on F1-score and Recall.

---

## Dataset

[Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## Dependencies

```
pip install pandas numpy seaborn matplotlib scikit-learn xgboost kagglehub
```
