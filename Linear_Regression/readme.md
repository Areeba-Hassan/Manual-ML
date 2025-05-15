# Manual Linear Regression — Medical Insurance Cost Prediction

## What is Linear Regression?

Regression is a basic machine learning technique that helps us predict a continuous number based on input data.
This is like drawing the best possible line through a bunch of pointsto determine the expected value of something — medical insurance charges, in our case — given features like age, BMI, smoking status, and more.

In this project, we implement Linear Regression manually from scratch without relying on any machine learning libraries. That means:

- We write the code to calculate the weights, and then predict outputs by multiplying features with weights.
- We calculate how wrong our predictions are using a metric called Root Mean Squared Error (RMSE).
- We engineer features like interaction terms and polynomial terms (like BMI squared) to capture complex relationships.
- We use log-transformations on the target variable to handle skewed data and make learning smoother.

## What’s in this project?

The goal is to predict insurance charges for individuals based on their demographic and health data. Our features include:

- Age  
- BMI (Body Mass Index)  
- Number of children  
- Smoking status (converted to 0/1)  
- Sex (one-hot encoded)  
- Interaction between BMI and smoking  
- Polynomial terms (e.g. BMI squared)

We:

1. Preprocess and clean the data, including feature engineering.
2. Split the data into training, validation, and test sets.
3. Train a linear regression model manually.
4. Evaluate the model performance on all data splits using RMSE.
5. Compare predicted charges with actual charges visually using histograms.
6. Make predictions on new, unseen data.

## Why manual?

This isn’t about using fancy libraries. It’s about understanding the core math and coding behind how regression works. By doing everything manually, you get to see exactly what’s going on under the hood.
(this is for learning purposes)

The data use in the project is available via https://www.key2stats.com/data-set/view/1552
