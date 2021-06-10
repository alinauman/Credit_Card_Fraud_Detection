# Credit_Card_Fraud_Detection
In this project we have implemented Logistic Regression in Python to detect card fraud.

### What is Credit Card Frauds impact?
Credit card frauds are more common than you think, and lately, they’ve been on the higher side. Figuratively speaking, we’re on the path to cross a billion credit card users by the end of 2022. But thanks to the innovations in technologies like Artificial Intelligence, Machine Learning, and Data Science, credit card companies have been able to successfully identify and intercept these frauds with sufficient accuracy.

### What is the idea behind this implementation?
Simply put, the idea behind this is to analyze the customer’s usual spending behavior, including mapping the location of those spendings to identify the fraudulent transactions from the non-fraudulent ones. In this project we have implemented Logistic Regression as a base model to classify between Fraud and Non-Fraud transactions.

### How does the data look-like?
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

[Data-Set](https://www.kaggle.com/mlg-ulb/creditcardfraud)

### What is Logistic Regression?
[Logistic regression](https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-logistic-regression/#:~:text=Logistic%20regression%20is%20the%20appropriate,variable%20is%20dichotomous%20(binary).&text=Logistic%20regression%20is%20used%20to,or%20ratio-level%20independent%20variables.) is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary).  Like all regression analyses, the logistic regression is a predictive analysis.  Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.

[Implementation](https://github.com/alinauman/Credit_Card_Fraud_Detection/blob/main/Credit%20Card%20Fraud%20Detection%20Using%20Python.ipynb)

