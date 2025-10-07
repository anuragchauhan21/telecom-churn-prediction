# 📞 Telecom Customer Churn Analysis and Prediction

## Project Overview

This project explores customer **churn behavior** for a telecom company. The goal is to understand why customers leave the service, uncover patterns in customer behavior, and **build a predictive model** to identify high-risk churners. </br> </br> The analysis combines **Exploratory Data Analysis (EDA)** and **Logistic Regression modeling** to provide actionable business insights.

## Objective

- Analyze customer behavior and service usage patterns
- Identify key drivers of churn
- Predict customers likely to churn
- Provide recommendations for reducing churn and improving customer retention

## Dataset

- Source: Kaggle
- Contains customer demographics, service usage, contract information, billing details, and churn status
- Preprocessing included handling missing values, converting categorical features to numerical format, and scaling where required

## Tools and Technologies

- Python, Pandas
- Seaborn, Matplotlib for visualization
- Scikit-learn for machine learning
- Google Colab

## Exploratory Data Analysis (EDA) Insights

- Churn rate is approximately 26.5%
- Senior citizens and month-to-month contract users are more likely to churn
- Electronic check payment users show higher churn than other payment methods
- Churn is highest in the initial months of tenure
- Customers with fewer services (0–3) tend to churn more, while those with 6+ services usually stay

## Logistic Regression Model

- Threshold set to *0.4 to maximize recall* for churners
- Overall accuracy: 0.70
- Recall for churners: 91%
- Precision for churners: 47%
- Confusion matrix shows good identification of churners with some false positives for non-churners

#### Key Features Influencing Churn

- Increasing churn: total charges, monthly charges, Internet services, online backup
- Reducing churn: contract type, tech support, phone service, tenure, online security

## Business Insights and Recommendations

- Customers with *high bills and fewer support services* are at higher risk of leaving
- Retention strategies could include *loyalty offers, improved support, and long-term contract incentives*
- Early identification of *high-risk customers* allows targeted engagement to reduce churn

## Files

- `Telecom_Churn_EDA.ipynb` – Exploratory analysis, visualizations, and insights
- `Telecom_Churn_Model.ipynb` – Model training, threshold tuning, feature influence, and predictions
- Dataset included for reference and reproducibility


## 👤 Author

Project by [**Anurag Chauhan**](https://www.linkedin.com/in/theanuragchauhan/)
