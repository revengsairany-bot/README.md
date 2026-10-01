# Customer Churn & Retention Analysis

## Project Overview

This project analyzes customer churn patterns for a telecommunications company using customer demographic, service, contract, tenure, and billing data.

The goal of this analysis is to identify customers at higher risk of churn, understand the factors associated with customer loss, and quantify the monthly charges associated with high-risk customers.

## Business Questions

- Which customer segments have the highest churn rates?
- How does customer tenure relate to churn?
- Which customer segments represent the highest churn risk?
- How much monthly revenue is associated with high-risk customers?
- What actions could the company take to improve customer retention?

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab

## Key Findings

### Overall Churn

- Total customers: 7,043
- Churned customers: 1,869
- Overall churn rate: 26.54%

Customers with 0–6 months of tenure had the highest overall churn rate at 53.3%.

### High-Risk Customer Segment

The analysis identified a high-risk segment consisting of customers with:

- Month-to-month contracts
- Fiber optic internet service

This segment contains:

- 2,128 customers
- 30.21% of the total customer base
- 1,162 churned customers
- 62.17% of all churned customers
- 54.61% churn rate

### Early-Tenure Risk

Within the high-risk segment, churn is particularly high among newer customers:

| Tenure | High-Risk Churn Rate |
|---|---:|
| 0–6 months | 74.2% |
| 7–12 months | 62.0% |
| 13–24 months | 50.6% |
| 25–48 months | 43.4% |
| 49–72 months | 29.3% |

This suggests that the first several months of the customer relationship represent a critical retention period.

### Monthly Charges Associated with Churn

The high-risk segment is associated with approximately 185,181 dollars in monthly charges.

Approximately 100,482 dollars in monthly charges are associated with customers in this segment who have churned.

These figures represent monthly charges associated with the customers, not guaranteed future revenue loss.

## Business Recommendations

### 1. Focus on Early-Tenure Customers

Within the high-risk segment, customers in their first six months have the highest churn rate at 74.2%.

The company could consider targeted onboarding programs, early customer check-ins, and retention offers during the first several months.

### 2. Prioritize the High-Risk Segment

Month-to-month customers using fiber optic service represent 30.21% of the customer base but account for 62.17% of all churned customers.

Retention efforts could prioritize this segment because of its concentration of churn.

### 3. Protect Recurring Revenue

The high-risk segment is associated with approximately 185,181 dollars in monthly charges, with 100,482 dollars associated with customers who have churned.

Reducing churn within this segment could help protect recurring customer revenue.

## Project Summary

This analysis examined customer churn patterns across customer tenure, contract type, internet service, and monthly charges.

The analysis identified a high-risk customer segment consisting of month-to-month customers with Fiber optic internet service. This group represents 30.21% of the customer base but accounts for 62.17% of all churned customers.

Churn within this high-risk segment is highest among customers with less than six months of tenure, reaching 74.2%.

The findings suggest that retention efforts could focus on early-tenure customers and the high-risk segment while monitoring the recurring monthly charges associated with customer churn.

## Project Files

- [Customer Churn & Retention Analysis](Customer_Churn_%26_Retention.ipynb)

## Author

**Reveng**

Aspiring Data Analyst focused on using data analysis and visualization to identify business insights and support data-driven decisions.
