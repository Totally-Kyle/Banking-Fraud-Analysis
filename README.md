# Banking-Fraud-Analysis

# Hypothesis
In this project I will find which tranaction types has the highest rate of fraudulent activity. Most lilely it'll be the transfer type becuae the ones committing the fraud will need to transfer the money out before it can be detected

# Project overview
In this Projetct I will be using EDA, machine learning and modeling to detect fraudulent transaction in th banking data. This project isn't just to identifying fraud but also predicting which transaction type will most likely have fraudulent activities.

# Exploratory Data Analysis
99.9% of the data is non-fraudulent and 0.01% is fraudulent.

There are 5 transaction types in the dataset with payment and cash_out having the most activity and debit being the least

The tranasaction types with the highest rate of Fraudulent activity are the transfer and cash_out types

The isFlaggedFraud column showed that it was the transfer type that had the actual highest rate of fraud 

# Cleaned Data
The step, nameDest, nameOrig, and isFlaggedFraud columns were removed before making the model

The nameDest and nameOrig columns were string values that wouldn't have made the predictions anymore accurate 

# Modeling
Logistic Regression - Accuracy: 0.9992

Logistic Regression - Precision: 0.9120

Logistic Regression - Recall: 0.4684

Logistic Regression - F1_Score: 0.6189
