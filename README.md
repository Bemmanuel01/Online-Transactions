# Online-Transactions
Online Payment Fraud Detection Using Machine Learning

In recent times, the trend of online payments is experiencing significant growth. This method offers buyers numerous benefits, including time savings and the convenience of not having to carry cash. However, these advantages come with potential downsides.

One major concern is the risk of fraud, which can occur with any payment application. Consequently, robust online payment fraud detection is essential to protect users and ensure trust in these systems.

This project uses various models to determine fraudulent transactions which can help online marchants and financial institutions who have become victims of fraud at one point or the order.

The data set possess the following features and their description;

# Feature Descriptions
- step: Indicates the unit of time for the transaction.
- type: Specifies the type of transaction conducted.
- amount: Represents the total amount of the transaction.
- name (Org): The account name of the sender initiating the transaction.
- oldbalance (Org): The sender's account balance before the transaction.
- newbalance (Org): The sender's account balance after the transaction.
- name (Dest): The account name of the recipient receiving the transaction.
- oldbalance (Dest): The recipient's account balance before the transaction.
- newbalance (Dest): The recipient's account balance after the transaction.
- isFraud: The target value to be predicted, indicating fraud status (0 for no fraud, 1 for fraud).

# Model Training

Given that the target value is a classification problem, we will utilize the following models:
- Logistic Regression: This model predicts the probability that a given data point belongs to a specific category.
- XGBClassifier: This refers to Gradient Boosted Decision Trees. In this algorithm, decision trees are created sequentially, with weights assigned to all independent variables, which are then used to make predictions.
- SVC (Support Vector Classification): SVC aims to identify a hyperplane in an N-dimensional space that distinctly classifies data points, providing outputs based on the nearest elements.
- Random Forest Classifier: This model constructs a collection of decision trees from a randomly selected subset of the training data. It then aggregates the votes from these decision trees to determine the final prediction.
