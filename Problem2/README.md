Overviwe:
Predict whether a customer will subscribe to a term deposit using Logistic Regression.

Dataset:

The dataset used is the Bank Marketing Dataset, containing 45,211 records and 17 attributes.

🔹 Key Features:
Age
Job
Marital status
Balance
Duration
Campaign details
🔹 Target Variable:
y = yes → Subscribed
y = no → Not subscribed
🔹 Class Distribution:
No: 39,922
Yes: 5,289

Approach
Data preprocessing (encoding categorical variables)
Logistic Regression for binary classification
Train-test split (80/20)
 Methodology
🔹 1. Data Cleaning
Checked for missing values
Ensured correct data types
🔹 2. Feature Encoding
Converted categorical variables using get_dummies()
Transformed target variable:
yes → 1
no → 0
🔹 3. Model Training
Used Logistic Regression with increased iterations
Trained on 80% of the dataset
🔹 4. Prediction
Predicted outcomes on test dataset
🔹 5. Evaluation
Accuracy Score
Confusion Matrix
Classification Report
Results
 Accuracy
0.8986 (~90%)
Confusion Matrix
[[7751  201]
 [ 716  375]]
Classification Report
Class	Precision	Recall
No (0)	0.92	0.97
Yes (1)	0.65	0.34
Findings:
The model achieves high overall accuracy (~90%).

