# Credit Card Fraud Detection <br>
To help the credit card company detect fraud cases and flag them out or send alerts to the customer. This helps in reduction of fraud cases and ensures that customers are<br>
not wrongly charged. In order to help the company detect such cases, application of machine learning models needs to be applied here.<br>

# Dataset description <br>
The dataset is taken from Kaggle datasets. Here is the [link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) for the same. The dataset contains transactions made by credit cards in September 2013 by European cardholders.<br>
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class(frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. 
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Steps Involved <br>
1. Importing the required packages in the environment(jupyter notebook used to code in Python)
2. Importing the Data
3. Data Cleaning and Processing to our needs and Exploratory Data Analysis
4. Figuring what type of Machine learning model would be required(Classification used here, covered in the next section)
5. Feature Selection and Data Split 
6. Building different classification models using sci-kit library
7. Evaluating the different models created and choosing the best model for training based on the results from the evaluation

# Machine Learning model <br>
Applying Classification model than any other model works here as such is the case with dataset. Classification is the process of predicting discrete variables (binary, Yes/No, etc.)
