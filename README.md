# Customer Churn Prediction & Retention Intelligence

## Overview

An end-to-end Data Science project focused on predicting customer churn and identifying customer characteristics associated with leaving a telecom company.

The project aims to help businesses understand customer behavior, identify high-risk customers, and support data-driven retention strategies.

## Objectives

- Explore and analyze customer behavior.
- Identify factors associated with customer churn.
- Develop and compare machine learning classification models.
- Evaluate models using appropriate classification metrics.
- Explain model predictions using SHAP.
- Develop an interactive application for churn risk prediction.

## Dataset

**IBM Telco Customer Churn Dataset**

The dataset contains 7,043 customer records with information about customer demographics, services, contracts, billing, and churn status.

Download the dataset from:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Place the CSV file in `data/raw/`.

## Current Progress

- [x] Initial data exploration
- [x] Data quality investigation
- [x] Handling missing values in `TotalCharges`
- [x] Churn distribution analysis
- [x] Contract type and churn analysis
- [x] Customer tenure analysis
- [x] Monthly charges analysis
- [ ] Payment method and internet service analysis
- [ ] Feature engineering and preprocessing
- [ ] Machine learning model development
- [ ] Model evaluation and explainability
- [ ] Interactive application development
- [ ] Deployment

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- Streamlit

## Project Structure

```text
customer-churn-prediction/
├── data/
├── notebooks/
├── src/
├── models/
├── reports/
├── requirements.txt
├── README.md
└── .gitignore
```

## Project Status

Currently in the Exploratory Data Analysis phase.

This project is being developed as a Data Science portfolio project.