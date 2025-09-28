# Online Payments Fraud Detection with Machine Learning

## Problem Statement
Online payment systems are convenient but vulnerable to fraud, especially in credit card transactions. Detecting fraudulent transactions is crucial for financial institutions to protect their customers and reduce losses.

The goal of this project is to develop a machine learning model that can classify online transactions as fraudulent or non-fraudulent using historical transaction data.

## Dataset
The dataset is sourced from **Kaggle** and contains historical transactions, including fraudulent and genuine ones.

**Columns:**
- `step` → Time unit (1 step = 1 hour)  
- `type` → Type of transaction (CASH_OUT, PAYMENT, CASH_IN, TRANSFER, DEBIT)  
- `amount` → Transaction amount  
- `nameOrig` → Customer initiating the transaction  
- `oldbalanceOrg` → Balance before the transaction  
- `newbalanceOrig` → Balance after the transaction  
- `nameDest` → Recipient of the transaction  
- `oldbalanceDest` → Recipient’s balance before the transaction  
- `newbalanceDest` → Recipient’s balance after the transaction  
- `isFraud` → Fraud indicator (0 = No Fraud, 1 = Fraud)  
- `isFlaggedFraud` → Flagged by the system (0/1)  

## Project Overview
This project involves the following steps:

- **Data Loading and Cleaning** – Read CSV, check for nulls, fix headers  
- **Exploratory Data Analysis (EDA)** – Visualize transaction types and distributions  
- **Data Transformation** – Map categorical columns to numeric, convert labels  
- **Correlation Analysis** – Identify features most correlated with fraud  
- **Model Building** – Decision Tree Classifier for fraud prediction  
- **Prediction** – Test model on sample transactions  

## Tools & Technologies
- Python  
- pandas, numpy, plotly, scikit-learn  
- Machine Learning: Decision Tree Classifier  
- Visualization: Plotly  

## How to Use This Project
1. **Clone the repository:**  
```bash
git clone https://github.com/Nisba833/-Online-Payments-Fraud-Detection.git
2.Open the Jupyter Notebook:
Online_Payments_Fraud_Detection.ipynb
3.Run each cell to see the analysis, visualizations, and machine learning model in action.

## Results
- The Decision Tree Classifier successfully predicts fraudulent transactions.
- Visualizations provide insights into risky transaction types.

## GitHub Repository :https://github.com/Nisba833/-Online-Payments-Fraud-Detection
 
