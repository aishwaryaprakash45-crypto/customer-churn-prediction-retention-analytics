# Customer Churn Prediction & Retention Analytics

## Overview

An end-to-end machine learning project that predicts telecom customer churn,
segments customers by churn risk, and analyzes potential retention revenue.

## Dataset

- 7,043 customers
- 21 columns
- Customer demographics
- Services and contracts
- Payment information
- Monthly and total charges
- Churn status

## Methodology

- Data cleaning and preprocessing
- Exploratory Data Analysis
- Feature analysis
- Logistic Regression
- Random Forest
- Model evaluation
- Churn probability threshold analysis
- Customer risk segmentation
- Revenue impact analysis

## Key Results

### Logistic Regression

- ROC-AUC: **0.8421**
- Recall at 0.30 threshold: **75.40%**
- F1 Score: **61.50%**

### Random Forest

- Accuracy: **78.35%**
- ROC-AUC: **0.8227**

## Key Business Finding

The highest observed churn segment was:

**Month-to-month contract + Fiber optic internet**

Observed churn rate:

**54.61%**

The High Risk segment had an actual churn rate of:

**71.8%**

## Revenue Impact

The high-risk segment represented:

**185,181.10 in monthly charges**

Illustrative retention scenarios estimated:

- 10% retention → 10,048.20/month
- 20% retention → 20,096.40/month
- 30% retention → 30,144.60/month

## Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook

## Business Objective

The goal is to use churn predictions to prioritize retention efforts and
support data-driven customer management.

**Customer Data → Churn Prediction → Risk Segmentation → Retention
Prioritization → Revenue Impact**
