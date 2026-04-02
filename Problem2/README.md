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
Yes: 5,289 The dataset is imbalanced, which affects model performance.

Approach
Data preprocessing (encoding categorical variables)
Logistic Regression model used for binary classification
Train-test split (80/20)
Methodology
Data Cleaning
Checked for missing values
Ensured correct data types
Feature Encoding
Converted categorical variables using get_dummies()
Transformed target variable:
yes → 1
no → 0
Model Training
Used Logistic Regression with increased iterations
Trained on 80% of the dataset
Prediction
Predicted outcomes on test dataset
Evaluation
Accuracy Score
Confusion Matrix
Classification Report
Results
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
Recall: 0.34
Findings
The model achieves high overall accuracy (~90%).
