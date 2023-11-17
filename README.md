# Credit-Card-Default-Prediction
This project addresses the critical issue of credit card defaults, a challenge that poses significant risks to lending institutions. Led by 'Rohit,' the project aims to develop an innovative model that identifies patterns and early warning signs of potential credit card defaults. The primary objectives include minimizing financial losses for lending institutions, enhancing the stability of the credit card industry, protecting the financial health and credit scores of card users, reducing legal and administrative expenses tied to defaulted payments, safeguarding the reputation and trust of lending institutions, and preventing fraudulent activities associated with credit card defaults. The project seeks to contribute to the development of effective strategies to tackle this pressing issue and promote a more secure and resilient credit card environment.
# Credit Card Default Prediction Project

## Overview:
This project addresses the critical issue of credit card defaults and aims to develop a model that identifies patterns and early warning signs of potential defaults. Led by Rohit Dhawale, the project utilizes a dataset sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients). The dataset includes numerical and categorical variables related to credit card usage, payment history, and default status.

## Data Pre-processing:
- Data cleaning steps include checking for missing values, duplicates, data types, outliers, and statistics.
- Categorical features are converted to numerical for model application.
- Exploration of defaulted customer distributions based on features like Gender, Education, Marriage, and Age.

## Problem Statement:
Credit card defaults pose significant challenges to lending institutions, leading to financial losses and potential damage to reputation. The project aims to minimize these challenges by developing strategies to reduce credit card defaults.

## Objectives:
- Develop a model to identify patterns and warning signs of credit card defaults.
- Minimize financial losses for lending institutions.
- Enhance stability in the credit card industry.
- Protect credit card users' financial health and credit scores.
- Reduce legal and administrative expenses.
- Safeguard the reputation and trust of lending institutions.
- Prevent fraudulent activities associated with credit card defaults.

## Data Modeling:
- Preprocessed data is converted to a CSV file for modeling tasks.
- Models are compared based on F1 scores, with Random Forest achieving the highest score (83.41%).

## Model Recommendation:
Considering the F1 scores and ease of use, Random Forest is recommended for credit card payment default prediction. It offers high performance, simplicity, and interpretability, aligning well with the project's goals.

## Business Impact Summary:
The F1 score is chosen as the preferred performance metric due to its ability to balance precision and recall, consider cost sensitivity, and reflect the business impact of credit card defaults. The Random Forest model, with an 83.41% F1 score, is selected for its performance, ease of use, and interpretability, contributing to the project's objectives of minimizing financial losses and protecting the interests of lending institutions and credit card users.
