# Lab 6: Linear Regression

## Objective

To implement and evaluate a Linear Regression model for predicting continuous numerical values.
This lab demonstrates the workflow of a machine learning project, from initial data exploration to model training and performance evaluation, using housing market data and an ecommerce customer dataset.

## Techniques Applied

### Exploratory Data Analysis (EDA)

* Performed initial data assessments using `info()` and `describe()`
* Used visual plotting techniques to identify correlations and data distributions

### Data Preparation

* Defined feature matrices (**X**) and target vectors (**y**)
* Example tasks:

  * Predicting housing prices based on area demographics
  * Predicting ecommerce spending based on customer behavior

### Model Training

* Implemented the `LinearRegression` algorithm from Scikit-Learn

### Model Evaluation

* Evaluated model performance using:

  * Mean Absolute Error (**MAE**)
  * Mean Squared Error (**MSE**)
  * Root Mean Squared Error (**RMSE**)

### Practical Application

* Applied the regression workflow to the Ecommerce Customers dataset
* Predicted **Yearly Amount Spent** based on:

  * Membership length
  * Time spent on the app

## Files Included

* `ARTI308 Lab6.ipynb` — Jupyter Notebook containing full regression analysis, model training, and evaluation steps
* `Ecommerce Customers` — Dataset containing customer behavior metrics used for the regression task
