# Telco Customer Churn Analysis

## 📌 Project Overview

Analyzed customer churn data from a telecommunications company to identify the key factors associated with customer churn and high-risk customer segments.

The analysis focuses on customer tenure, contract type, internet service, payment method, and monthly charges.

## 🎯 Business Objective

Identify customer groups with higher churn rates and uncover patterns that could help a telecom company improve customer retention.

## 📊 Dataset

- 7,043 customer records
- 33 original attributes
- Customer demographics
- Service subscriptions
- Contract information
- Payment methods
- Monthly and total charges
- Churn information

## 🔍 Key Findings

- Overall churn rate: **26.54%**
- Month-to-month customers had a **42.71% churn rate**, compared with **11.27%** for one-year contracts and **2.83%** for two-year contracts.
- Customers with **0–6 months tenure** had a **52.94% churn rate**.
- Fiber optic customers had a **41.89% churn rate**, compared with **18.96%** for DSL customers.
- Electronic-check customers had a **45.29% churn rate**.
- Customers paying **$60–90 per month** had a **33.91% churn rate**.
- The highest-risk identified segment was customers with **0–6 months tenure + month-to-month contract + fiber optic service**, with a **74.15% churn rate**.
- This segment contained **619 customers** and accounted for **459 churned customers**, representing **24.56% of all churned customers**.

## 📈 Analysis Performed

- Data cleaning and validation
- Missing-value analysis
- Duplicate detection
- Churn-rate analysis
- Customer segmentation
- Contract analysis
- Tenure analysis
- Internet-service analysis
- Payment-method analysis
- Monthly-charge analysis
- Multi-factor churn segmentation
- Data visualization

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel

## 📁 Project Structure

```text
customer-churn-analysis/
│
├── data/
│   └── raw/
│       └── Telco_customer_churn.xlsx
│
├── data_cleaned/
│   └── telco_customer_churn_cleaned.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
├── README.md
└── .gitignore

💡 Business Insight

The analysis indicates that churn is concentrated among newer customers, particularly those on month-to-month contracts. Combining tenure, contract type, and internet service reveals specific customer segments with substantially higher observed churn rates.

These findings can help prioritize customer-retention analysis and targeted engagement strategies.

👤 Author

Sai Snigdha
