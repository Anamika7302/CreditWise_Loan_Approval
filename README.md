
### Project Overview

The Credit Wise Loan System is an end-to-end Machine Learning solution designed to automate and optimize loan approval decisions for financial institutions.

Traditionally, loan approvals rely on manual verification — leading to slow processing, human bias, inconsistent risk assessment, and potential financial losses.

This project builds an intelligent classification system that predicts whether a loan should be Approved (1) or Rejected (0) based on applicant financial and demographic data.


### Business Problem

A financial institution processes hundreds of loan applications daily.

Manual verification causes:

❌ Good customers being rejected (lost revenue)

❌ High-risk customers being approved (financial loss)

❌ Slow processing time

❌ Inconsistent decision-making

The goal is to introduce an AI-powered system that:

-> Learns from historical data

-> Identifies hidden approval patterns

-> Provides unbiased, fast, data-driven decisions

-> Assists loan officers before final verification


### Objectives

-> Perform exploratory data analysis on structured loan data

-> Engineer meaningful financial risk indicators

-> Build classification models for loan approval prediction

-> Compare multiple ML algorithms

-> Evaluate using industry-relevant metrics

-> Provide interpretable credit risk insights


### Dataset Description

| Feature            | Description                         |
| ------------------ | ----------------------------------- |
| Applicant_Income   | Monthly income                      |
| Coapplicant_Income | Co-applicant income                 |
| Employment_Status  | Salaried / Business / Self-employed |
| Credit_Score       | Bureau score                        |
| DTI_Ratio          | Debt-to-Income ratio                |
| Existing_Loans     | Active loans                        |
| Savings            | Savings balance                     |
| Collateral_Value   | Collateral provided                 |
| Loan_Amount        | Requested amount                    |
| Loan_Term          | Loan duration                       |
| Loan_Purpose       | Home / Education / Business         |
| Property_Area      | Urban / Semi-Urban / Rural          |
| Loan_Approved      | Target (1 = Approved, 0 = Rejected) |


### System Architecture / Workflow

Raw Dataset
     ↓
Data Cleaning & Preprocessing
     ↓
Feature Engineering
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Prediction & Risk Scoring



### Technologies Used


Python 3.x

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook



### Model Development

 Algorithms Used

-> Logistic Regression
-> K Neighbour Classifier
-> GB Naive Bayes 



### Evaluation Metrics

Accuracy

Precision

Recall

F1-Score



### Results & Performance

| Model                   | Accuracy | Precision | Recall | F1 Score |
| -------------------     | -------- | --------- | ------ | -------- |
| Logistic Regression     | 0.875    | 0.79      | 0.80   | 0.796    |
| K Neighbour Classifier  | 0.755    | 0.62      | 0.508  | 0.558    |
| GB Naive Bayes          | 0.865    | 0.783     | 0.7704 | 0.7768   |
