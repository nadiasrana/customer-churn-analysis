# Customer Churn Analysis

## Overview
This project analyzes ecommerce customer behavior data to understand what patterns are associated with churn and retention.

## Business Question
Which customer behaviors are most strongly associated with churn, and how can those signals be used to identify at-risk users?

## What I Did
- Cleaned and prepared customer data using Python
- Removed duplicates and handled missing numeric values with median imputation
- Compared churned and retained users across engagement and purchase metrics
- Built visualizations for login frequency, session duration, pages per session, and purchases
- Created a simple churn risk score based on behavioral activity
- Explored churn patterns across customer membership length

## Tools Used
- Python
- pandas
- NumPy
- matplotlib
- Jupyter Notebook

## Key Insights
- Customers who churn tend to log in less frequently
- Lower session duration and fewer purchases are associated with higher churn
- Engagement metrics provide useful early warning signs of retention risk
- A simple churn risk score can help highlight users who may need re-engagement

## Limitations
This project uses a heuristic churn risk score rather than a predictive machine learning model. A strong next step would be building and validating a churn prediction model on unseen data.

## Why It Matters
Understanding churn helps companies identify at-risk users earlier and improve retention strategy through better engagement and targeted interventions.
