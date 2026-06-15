# B2B Customer Churn Predictive Pipeline & Retention Architecture

## 📈 Executive Summary & Business Intent
In high-growth B2B, SaaS, and Fintech environments, customer attrition is a critical threat to Monthly Recurring Revenue (MRR) and Lifetime Value (LTV) maximization. This repository contains an end-to-end predictive analytics framework designed to proactively detect accounts at risk of churning. 

By transitioning transactional data into predictive assets, this diagnostic architecture establishes a baseline data cleaning pipeline, handles severe multicollinearity, and tests controlled classification models. The ultimate objective is to provide sales development, customer success, and account management teams with actionable data to execute proactive retention plays before revenue leaks occur.

---

## 🛠️ Repository Architecture & File Directory

The production-ready codebase is systematically organized into chronological engineering phases:

```text
customer-churn-predictive-pipeline/
├── README.md
├── data/
│   └── ChurnData_grupoA.csv (Data Infrastructure Baseline)
└── core_notebooks/
    ├── 01_customer_churn_preprocessing.ipynb
    └── 02_predictive_churn_modeling.ipynb
