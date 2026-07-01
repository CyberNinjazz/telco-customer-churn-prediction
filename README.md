# Telecom Customer Churn Prediction  
Author: Shannon Storts  

## Overview  
Predict customer churn (Yes/No) using classification models to identify at-risk customers and support retention strategies.

## Models  
- Logistic Regression  
- K-Nearest Neighbors (k = 12)  

## Results  
- Logistic Regression Accuracy: 78.75%  
- KNN Accuracy: 77.68%  
- Cross-validation Accuracy: 80.69%  
- Recall (Churn): 0.52 (Logistic), 0.48 (KNN)  

## Key Insights  
- Longer tenure strongly reduces churn  
- Month-to-month contracts increase churn risk  
- Fiber Optic service is a major driver of churn  

## Business Impact  
Identifying high-risk customers allows companies to take targeted retention actions, reducing churn and improving long-term revenue.

## Tech Stack  
- Python (pandas, numpy)  
- scikit-learn  
- matplotlib / seaborn  

## Data  
- [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

