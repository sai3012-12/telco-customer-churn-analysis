# Telco Customer Churn Analysis

## Project Overview

This project analyzes customer churn for a telecommunications company using 7,043 customer records.

The goal was to identify customer characteristics and segments associated with higher churn and turn the analysis into actionable business insights.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel/CSV

## Dataset

The dataset contains 7,043 customers and 33 original columns covering:

- Customer demographics
- Tenure
- Contract type
- Internet service
- Payment method
- Monthly charges
- Total charges
- Churn information
- Customer lifetime value

## Data Cleaning

The dataset was inspected and cleaned before analysis.

Key steps included:

- Checked dataset dimensions and data types
- Identified missing values
- Investigated blank Total Charges values
- Converted Total Charges to numeric format
- Checked for duplicate records
- Validated categorical variables
- Created analysis-ready customer segments

The cleaned dataset was saved separately from the original raw data.

## Key Findings

### Overall Churn

The overall churn rate was:

**26.54%**

### Contract Type

Observed churn rate by contract:

- Month-to-month: **42.71%**
- One year: **11.27%**
- Two year: **2.83%**

### Customer Tenure

Observed churn decreased substantially across tenure bands:

- 0–6 months: **52.94%**
- 7–12 months: **35.89%**
- 13–24 months: **28.71%**
- 25–48 months: **20.39%**
- 49–72 months: **9.51%**

### Internet Service

Observed churn rate:

- Fiber optic: **41.89%**
- DSL: **18.96%**
- No internet service: **7.40%**

### Payment Method

Electronic check customers had an observed churn rate of **45.29%**, compared with:

- Mailed check: 19.11%
- Bank transfer: 16.71%
- Credit card: 15.24%

### High-Risk Customer Segment

The analysis identified a particularly high-churn segment:

**0–6 months + Month-to-month contract + Fiber optic**

- Customers: **619**
- Churned customers: **459**
- Observed churn rate: **74.15%**
- Share of all churned customers: **24.56%**

## Business Insights

The analysis suggests that customer churn is strongly associated with several customer characteristics, particularly:

1. Short customer tenure
2. Month-to-month contracts
3. Fiber optic internet service
4. Higher monthly charges
5. Electronic-check payment

The interaction analysis showed that customer characteristics can be more informative when analyzed together rather than independently.

For example, customers in their first six months with a month-to-month contract and fiber optic service had a substantially higher observed churn rate than the overall customer population.

These findings can help a telecom business prioritize retention analysis and investigate targeted onboarding and retention strategies.

## Project Structure

```text
customer-churn-analysis/
│
├── data/
│   └── raw/
│       └── Telco_customer_churn.xlsx
│
├── data_cleaned/
│   ├── telco_customer_churn_cleaned.csv
│   └── telco_customer_churn_analysis.csv
│
├── notebooks/
│   └── churn_analysis.ipynb
│
└── README.md