# Customer Churn Analysis

This project analyzes customer churn behavior using SQL, Python, and a simple predictive model.

**Tools:** SQL (SQLite) · Python (pandas, matplotlib, scikit-learn) · Logistic Regression  

---

## What This Project Does
Analyzed 7,043 telecom customers to understand why customers leave and which ones are most at risk.  

Used SQL for initial data exploration, Python for EDA and visualization, and logistic regression to identify the key drivers of churn.

---

## Key Findings
- Month-to-month customers churn at ~43%, compared to 11% for one-year and 3% for two-year contracts  
- Churned customers are heavily concentrated in the first 10 months of tenure  
- Churned customers average about $74/month vs $61/month for retained customers  

---

## Business Recommendation
Focus retention efforts on month-to-month customers in their first year.  

A 5% reduction in churn for this group would retain ~83 customers and recover about $66,000 in annual revenue.

---

## Files
- `customer_churn_analysis.ipynb` — full analysis notebook  
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — source data (Kaggle Telco dataset)
