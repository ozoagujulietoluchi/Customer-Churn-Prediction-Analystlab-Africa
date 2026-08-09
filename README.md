# Customer-Churn-Prediction
## Analystlab-Africa Machine Learning Internship

### Week 1 Machine Learning Internship Project: Customer Churn Prediction using the Telco Customer Churn dataset.


## Project Overview

This project was completed as part of Week 1 of the AnalystLab Africa Machine Learning Internship Programme.

The project focuses on understanding and framing a customer churn prediction problem using the Telco Customer Churn dataset.

The objective is to determine how machine learning can be used to identify customers who are at risk of leaving a telecommunications service provider, allowing the business to develop proactive customer retention strategies.

## Business Problem

ABC Communications Ltd wants to predict which existing customers are likely to churn before they leave the company.

A predictive model could help the company identify customers at higher risk of churn and support proactive retention strategies.

## Machine Learning Problem

This is a supervised binary classification problem.

The target variable is:

* `Churn = Yes`: Customer churned
* `Churn = No`: Customer did not churn

## Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains 7,043 customer records and 21 variables.

The target variable is `Churn`.

The `customerID` variable is treated as an identifier and is excluded from the predictive features.

## Data Understanding

The dataset contains demographic, account, service, contract and billing information.

Important data-quality observations include:

* 7,043 observations
* 21 columns
* No duplicate rows
* `customerID` contains unique customer identifiers
* `TotalCharges` is initially stored as an object/string variable
* 11 blank entries were identified in `TotalCharges`
* The target variable is imbalanced, with fewer customers in the churn class than the non-churn class

## Exploratory Data Analysis

The Week 1 analysis includes:

* Churn distribution
* Churn by selected categorical variables
* Distribution of numerical variables
* Correlation analysis of numerical variables

## Proposed Preprocessing

The planned preprocessing steps include:

1. Exclude `customerID`
2. Convert `TotalCharges` to a numerical variable
3. Handle missing values
4. Encode categorical variables
5. Scale numerical variables where appropriate
6. Use a stratified train-test split

## Candidate Machine Learning Algorithms

The following algorithms are proposed for future model development:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting / XGBoost

Logistic Regression will provide a baseline model, while tree-based ensemble methods will be evaluated as alternative approaches.

## Evaluation Metrics

The proposed evaluation metrics are:

* Recall
* Precision
* F1-score
* ROC-AUC
* Accuracy

Recall and F1-score will receive particular attention because identifying customers who are likely to churn is important for customer retention.

## Project Structure

```text
customer-churn-prediction-analystlab-africa/
│
├── README.md
├── notebooks/
│   └── Week1_Customer_Churn_Analysis.ipynb
├── reports/
│   ├── Business_Understanding_Report.pdf
│   ├── Dataset_Inspection_Report.pdf
│   └── Machine_Learning_Proposal.pdf
└── requirements.txt
```

## Learning Focus

This project focuses on:

* Business problem framing
* Data understanding
* Data quality inspection
* Exploratory data analysis
* Feature and target identification
* Classification problem formulation
* Machine learning model planning
* Evaluation metric selection

## Programme

AnalystLab Africa
Machine Learning Internship Programme
Week 1 Assignment
