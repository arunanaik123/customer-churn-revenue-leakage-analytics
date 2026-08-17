# Customer Churn & Revenue Leakage Analytics

## Business Question
Which customer segments are most likely to churn, and how much monthly recurring revenue is at risk as a result? This project identifies at-risk customers, quantifies the revenue exposure tied to predicted churn, and surfaces the service/contract factors driving it — turning a churn prediction into a dollar-denominated business problem.

## Dataset
[IBM Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) — 7,043 customers of a telecom provider, with tenure, contract type, services subscribed, monthly/total charges, and churn status.

## Approach
1. **Data Cleaning & EDA** — handle missing values, type corrections, churn rate overview
2. **Cohort & Retention Analysis** — tenure-based cohorts, retention curves by contract type and service tier
3. **Predictive Modeling** — logistic regression / decision tree to classify churn risk
4. **Revenue Leakage Estimation** — translate predicted churn into monthly recurring revenue at risk, segmented by customer group

## Tech Stack
Python (pandas, numpy, scikit-learn, lifelines), matplotlib/seaborn for visualization, Jupyter notebooks.

## Key Findings
_[to be filled in after analysis]_

## Repo Structure
```
├── data/raw/              # Raw Kaggle dataset
├── notebooks/              # Analysis notebooks, run in order (01 → 04)
├── src/                     # Reusable data prep, feature engineering, model code
└── reports/figures/        # Exported charts/visuals
```
