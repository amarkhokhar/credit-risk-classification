# credit-risk-classification

This project aims to determine the credit risk of loan applications using a logistic regression model. The model predicts whether a loan is healthy (0) or high-risk (1).

The loan data is read from a CSV file. The file contains various features relevant to assessing credit risk. The dataset is split into training and testing sets to evaluate the model's performance. 

Logistic regression is employed to build the predictive model. The training set is used to fit the model, allowing it to learn the relationships between the features and the target variable (credit risk).

The model's performance is evaluated using the following metrics:

Confusion Matrix: Provides insight into the number of true positives, true negatives, false positives, and false negatives.
Classification Report: Summarizes precision, recall, F1-score, and support for each class (healthy and high-risk loans).