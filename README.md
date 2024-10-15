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
