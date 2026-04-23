# Customer Churn Analysis

## Overview
This project analyzes ecommerce customer behavior to understand what drives churn and how user engagement impacts retention.

## Business Context
Customer churn represents users who stop engaging with a product or service. Identifying churn early allows companies to improve retention and reduce revenue loss.

## Key Questions
- What behaviors are associated with churn?
- How do churned users differ from retained users?
- Can we identify high-risk users using engagement data?

## Approach
- Cleaned and prepared customer dataset using Python
- Handled missing values using median imputation
- Compared churned vs retained users across:
  - login frequency
  - session duration
  - purchase behavior
  - engagement metrics
- Built visualizations to analyze patterns
- Created a churn risk score based on behavioral indicators

## Key Results
- Churned users showed lower login frequency and engagement
- Lower session duration was strongly associated with churn
- Purchase activity was one of the strongest indicators of retention
- Risk score successfully separated high-risk vs low-risk users

## Sample Visualizations

![Login Frequency](images/login_frequency.png)
![Purchases](images/purchases.png)

## Tools Used
- Python
- pandas
- NumPy
- matplotlib
- Jupyter Notebook

## Limitations
This project uses a simple heuristic churn risk score. A next step would be building a predictive machine learning model and validating performance.

## Future Improvements
- Build churn prediction model (Logistic Regression / Random Forest)
- Add feature importance analysis
- Deploy as dashboard or web app

## Why It Matters
Understanding churn helps companies proactively retain users and improve product experience.
