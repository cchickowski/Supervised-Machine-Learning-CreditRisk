# Supervised-Machine-Learning-CreditRisk

In this assignment, the goal was to build a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not.

Background
LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.


## Step 1: Preprocessing: Convert categorical data to numeric:
Created a training set from the 2019 loans using pd.get_dummies() to convert the categorical data to numeric columns. Similarly, create a testing set from the 2020 loans, also using pd.get_dummies(). 

## Step 2: Consider the models on Unscaled data:
Created and compared two models on this data without scaling: a logistic regression, and a random forest classifier. 

## Step 3: Scaled the data and revisited the models:
Scaled the data and then used the two models again(logisitic regression and random forest classifier) to score the data again. 

## Conclusion: 
Both models performed very similar with my data when both unscaled or scaled. The RandomForest classifier did perform slighly better when the data was scaled. The Logisitic regression model performed a little bit better with the unscaled data.
