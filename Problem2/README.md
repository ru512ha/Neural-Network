Objective:
Predict whether a customer will subscribe to a term deposit using Logistic Regression.

Dataset:
The dataset used is the Bank Marketing Dataset, containing 45,211 records and 17 attributes.
Key Features:
Age
Job
Marital status
Balance
Duration
Campaign details
Target Variable:
y = yes → Subscribed
y = no → Not subscribed
Class Distribution:
No: 39,922
Yes: 5,289

Approach
Data preprocessing (encoding categorical variables)
Logistic Regression model used for binary classification
Train-test split (80/20)

Methodology
1.Data Cleaning
oChecked for missing values
oEnsured correct data types
2.Feature Encoding
oConverted categorical variables using get_dummies()
oTransformed target variable:
yes → 1
no → 0
3.Model Training
Used Logistic Regression with increased iterations
Trained on 80% of the dataset
4.Prediction
Predicted outcomes on test dataset
5.Evaluation
Accuracy Score
Confusion Matrix
Classification Report

Results:
Accuracy: 0.8986 (~90%)
Confusion Matrix:
[[7751  201]
 [ 716  375]]
Classification Report:
Class 0 (No):
Precision: 0.92
Recall: 0.97
Class 1 (Yes):
Precision: 0.65
Findings
The model achieves high overall accuracy (~90%).




