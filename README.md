# PayPal

# Description

Credit card companies must recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. Credit card fraud is a fascinating subject for data scientists because of the enormous data sets, real and costly business implications, and potential to solve significant business problems that save millions and millions of dollars/pounds/euros/money.

In global efforts to understand and improve machine learning models and data analysis approaches, some datasets have been made open source.

For this project, you will use a somewhat de-identified dataset of credit card transactions in Europe. The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced. The positive class (frauds) accounts for 0.172% of all transactions.

It contains only numerical input variables, which are the result of a PCA transformation. Unfortunately, we cannot provide the original features and more background information about the data due to confidentiality issues. Features V1, V2, … V28 are the principal components obtained with PCA. The only features that have not been transformed with PCA are 'Time' and 'Amount.' Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount; for example-dependant cost-sensitive learning. Feature 'Class' is the response variable, and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

You have been hired by FriendPay, a competitor of PayPal, to help them improve their credit card fraud identification system. They are having difficulty identifying which transactions are or are not fraudulent, and this is creating significant business problems that are costing them a lot in missed transaction fees.

**Your Mission**
Your mission is to build a fraud detection model using the dataset that has been provided and in doing so, increase revenue from transaction fees.

**What are the success criteria?**
During our next meeting, you will have to show us some data (plot? report?) of what you've been building.
You will also be evaluated on your model's impact on the business. We need to make our customers happy by denying fraudulent transactions and allowing genuine ones.

**What to expect?**
A presentation with slides on how you classified, as well as assumptions, implications, and other important information.
Code that the DevOps team should be able to push to production.

# Technical specification

Companies that involve a lot of transactions with the use of cards need to find anomalies in the system. Build a fraud detection model on credit cards. Use the transaction and their labels as fraud or non-fraud to detect if new transactions made by the customer are fraud or not.

**Learning outcomes:** the five stages of your project

1. Data Collecting / Cleaning (see below)
2. Data Exploration
3. Data Visualization
4. Machine Learning
5. Communication
