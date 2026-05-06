# Customer Churn Analysis

In this project, I looked at customer churn in a telecom dataset to understand why customers leave and what factors are most related to churn.

**Tools:** SQL (SQLite) · Python (pandas, matplotlib, scikit-learn) · Logistic Regression  

---

## What This Project Does

Analyzed a telecom dataset with 7,043 customers to understand why customers leave and who is most at risk. 

Used SQL to explore the data and break down churn by contract type and tenure, and Python for data cleaning and visualization. 

Built a logistic regression model to identify the key drivers of churn.

---

## Interactive Dashboard

View the Tableau dashboard here:  
https://public.tableau.com/app/profile/huiyi.chen/viz/CustomerChurnAnalysisDashboard_17780192968040/CustomerChurnAnalysisDashboard

This dashboard brings together the main findings and highlights the key factors driving customer churn.

---

## Key Findings
- Month-to-month customers churn at ~43%, compared to 11% (one-year) and 3% (two-year contracts)
- Churned customers are heavily concentrated in the first 10 months of tenure  
- Churned customers average about $74/month vs $61/month for retained customers  

---

## Business Recommendation
Focus retention efforts on month-to-month customers, especially during their first year.

A 5% reduction in churn for this group would retain ~83 customers and recover about $66,000 in annual revenue.

---

## Files
- `customer_churn_analysis.ipynb` — full analysis notebook  
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — source dataset (Kaggle Telco Customer Churn)
