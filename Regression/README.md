# Prediction of Flight Delays

## Project/Goals
The goal of this project is to create a prediction model of flight delays. This model can be used to predict the amount of delay a certain flight may have one week in advance of the flight.

## Process
### EDA
First, exploratory data analysis was performed, where the raw dataset was examined along with its variables.
### Feature Engineering
Some new features were created using combinations/manipulations of existing features to be suitable for modeling.
### Modeling
Two models were created: A classification model to predict whether the flight will be delayed or not, and a regression model to predict the actual amount of the delay. A logistic regression algorithm was fitted to the classification model while a linear regression algorithm was fitted to the regression model.

## Results
The classification model predicts the delay with an accuracy score of 0.63, while the regression model predicts the delay with a mean average error of 23 minutes.