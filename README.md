# Loan Approval Predictor

Securing a personal bank loan can be challenging and time consuming. Conventional methods heavily rely on the credit score of an individual, potentially cutting off the deserving ones. This results in limited financial access for borrowers. This project aims to predict bank loan approvals using machine learning techniques. It involves building a predictive model to determine whether a loan application should be approved or denied based on various applicant features.

## Table of Contents

- [Overview](#overview)
- [Features](#features)

## Overview

The Bank Loan Approval Predictor is a machine learning project focused on creating a model that can assess loan applications and predict their approval or denial. It employs data preprocessing, EDA, model development, and evaluation to achieve this objective.

## Analysis

- Reading the CSV data from into python, parsing it using python control structures. 
- Loading the data into normalized database(SQLLite). 
- Using joins to fetch data from all the tables and loading into pandas. 
- Data Cleaning 
- Removed unwanted columns such as zip code and person_id. 
- Removed row items with negative value in year of experience, as it cannot be less than zero. 
- Checked for missing data, outliers. 
- Exploratory Data Analysis 
- CorrelaƟon plot. 
- We found that the data was unbalanced with 90% and 10% cases of No and Yes respectively. 
- Analyzing the relationship between the descriptors and target variables using different plots. 
- To resolve data imbalance, we performed SMOTE analysis.
- Trained 2 models, Logistic Regression and Random Forest with and without SMOTE analysis. 
- Evaluation metrics to assess the model's performance.
- Python-based implementation using libraries like Pandas, Scikit-learn, and Matplotlib.
- Jupyter Notebooks utilized for exploratory data analysis and model development.

