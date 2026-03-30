# Customer Churn Analysis

## Overview
This project looks at customer churn behavior using a telecom dataset. The goal was to understand why customers leave and what factors are most strongly associated with churn. I focused on identifying patterns that could realistically help a business reduce churn and protect revenue.

## Dataset
- Telco Customer Churn dataset (~7,000 customers)
- Includes customer demographics, contract type, tenure, and billing information
- Target variable: Churn (Yes/No)

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- SQL (for query-based analysis)
- Jupyter Notebook

## What I Did
- Cleaned and processed the dataset (handled missing values, converted data types)
- Created a churn flag for analysis
- Calculated overall churn rate
- Analyzed churn across different customer segments (contract type, tenure)
- Estimated revenue at risk from churned customers
- Built visualizations to highlight trends and patterns

## Key Findings
- Overall churn rate is around 26–27%
- Month-to-month customers have the highest churn (~43%)
- Customers in their first year have the highest churn (~48%)
- Monthly revenue at risk from churn is about $139K
- Month-to-month customers account for the majority of lost revenue (~87%)

## Takeaways
- Customers on flexible contracts are much more likely to leave
- Early-stage customers are the highest risk group
- Retention efforts should focus on onboarding and converting customers to longer-term contracts

## How to Run
1. Clone the repo
2. Install dependencies:
