# Customer-Churn-Analysis

## Overview
This project performs Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset to identify the key factors influencing customer attrition. The analysis includes data cleaning, visualization, correlation analysis, and feature importance using Random Forest.

## Dataset
- **Rows:** 7043
- **Columns:** 21
- **Target Variable:** Churn (Yes/No)

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Key Findings
- Customers with **Month-to-Month contracts** are more likely to churn.
- **Fiber Optic** users show higher churn rates.
- Customers without **Online Security** or **Tech Support** churn more frequently.
- **Electronic Check** is the most common payment method among churned customers.
- Higher **Monthly Charges** are associated with increased churn.
- Customers with **low tenure (1–12 months)** are at the highest risk of churn.
- Gender has minimal impact on churn.

## Feature Importance (Random Forest)
Top predictors of churn:
1. TotalCharges
2. MonthlyCharges
3. Contract_Month-to-month
4. tenure_group_1-12
5. TechSupport_No
6. OnlineSecurity_No
7. PaymentMethod_Electronic check
8. InternetService_Fiber optic

## Business Recommendations
- Encourage long-term contracts.
- Improve Fiber Optic customer experience.
- Promote Tech Support and Online Security services.
- Focus retention efforts on new customers.
- Incentivize automatic payment methods.

## Future Work
- Build churn prediction models (XGBoost, CatBoost, LightGBM).
- Deploy a churn prediction dashboard using Streamlit.
- Develop customer retention strategies based on predictions.

## Author
**Kasturi Rasekar**
