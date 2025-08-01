# Manual Logistic Regression — Customer Churn Prediction

## What is Logistic Regression?
Logistic Regression is a fundamental machine learning algorithm used for classification problems. Instead of predicting a continuous value, it estimates the probability that an instance belongs to a particular class (0 or 1).

## In this project, we implement Logistic Regression manually from scratch without using any machine learning libraries for the model itself. That means:
We write the code to initialize and update weights using gradient descent.
We use the sigmoid function to convert raw scores into probabilities.
We measure how wrong our predictions are using binary cross-entropy loss.
We implement early stopping based on the gradient norm to detect convergence.

## What’s in this project?
The goal is to predict whether a customer will churn (leave the service) based on their account details and service usage. Our features include:
Tenure
Monthly charges
Total charges
One-hot encoded categorical features like contract type, online security, payment method, senior citizen flag etc.

## We:
Preprocess and scale numeric features.
One-hot encode selected categorical variables.
Split the data into training and test sets.
Train a logistic regression classifier manually with gradient descent.
Evaluate the model using accuracy, confusion matrix, precision, recall, and F1-score.
Plot the training loss curve to visualize convergence.

## Why manual?
This isn’t about using high-level libraries like sklearn. It’s about learning the math and logic behind logistic regression step by step:
Writing the forward pass (z = Xw, sigmoid(z)) yourself.
Coding the gradient of the cross-entropy loss and weight updates manually.
Understanding how probabilities translate to classification decisions via thresholds.
By doing this from scratch, you see exactly what’s happening under the hood. (this is only for learning purposes! :) )
dataset used: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
