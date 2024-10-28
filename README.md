# Machine Learning Algorithms
## Overview
This project contains 3 main ML algorithms (Linear Regression, Logistic Regression and K nearest Neighbor) and their implementation using Juuypter Notebook.
### 1. Linear Regression 
Linear regression is a statistical method used for modeling the relationship between a dependent variable (often called the target or response variable) and one or more independent variables (also known as predictors or features). It’s a fundamental technique in predictive modeling and machine learning.

#### Evaluating the model
After fitting a linear regression model, its performance is evaluated using various metrics, such as:
- Mean Absolute Error (MAE): The average absolute difference between predicted and actual values.
- Mean Squared Error (MSE): The average of the squared differences between predicted and actual values.
- Root Mean Squared Error (RMSE): The square root of the average of the squared differences between predicted and actual values. It provides a measure of how well a model's predictions match the observed data.

#### Applications of Linear Regression
- Economics: Predicting consumer spending based on income.
- Real Estate: Estimating house prices based on features like size, location, and number of bedrooms.
- Health: Analyzing the relationship between weight and blood pressure.
- Finance: Forecasting stock prices based on market indicators.
#### Example
For instance, if you want to predict the price of a house based on its size, you would collect data on various houses,
with size as your independent variable and price as your dependent variable. By applying linear regression,
you can derive a model that predicts house prices based on size.

### 2. Logistic Regression
Logistic regression is a statistical method used for binary classification problems,
where the goal is to predict the probability that a given input belongs to a particular category.
Unlike linear regression, which predicts a continuous outcome, logistic regression predicts a categorical outcome, 
usually binary (0 or 1, true or false, yes or no).
#### Apllication of Logistic Regression
Logistic regression is widely used in various fields for binary classification tasks, including:
- Medical Diagnosis: Predicting the presence or absence of a disease based on diagnostic factors.
- Credit Scoring: Classifying loan applicants as likely to default or not based on their financial history.
- Marketing: Predicting whether a customer will respond to a marketing campaign.
- Spam Detection: Classifying emails as spam or not spam based on their content

### 3. K-Nearest Neighbor
KNN is a simple, yet powerful, instance-based learning algorithm used for both classification and regression tasks in machine learning.
The basic idea is to predict the class (or value) of a data point based on the classes (or values) of its k nearest neighbors in the feature space.
Steps of the KNN Algorithm
- Choose the number of k: Decide how many neighbors to consider.
- Calculate the distance: For a new data point, compute the distance to all points in the training dataset.
- Identify the nearest neighbors: Select the 𝑘 data points with the smallest distances.
- Make a prediction:
    > For classification, return the majority class among the k neighbors.
    > For regression, return the average (or median) value among the k neighbors.
