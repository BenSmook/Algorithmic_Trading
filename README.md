# Trading Algorithm Using Support Vector Classification

This project is an example of using Support Vector Classification or SVC from scikit-learn librarys 'svm' module for a classification problem.

## First 
 What you will need
  - Python3
  - Jupyter Notebook
  - pandas, numpy, matplotlib and sklearn

## Steps
Import the OHLCV dataset and generate trading signals using shot- and long-window SMA values. The data is then split into training and testing datasets.

The SVC classifier model is then fit on the training data, and the model's predictions on the testing data is used to evaluate the model using the classification report from scikit-learn library.

A predictions DataFrame is created that contains columns for "Predicted" values, "Actual Returns", and "Strategy Returns". A cumulative return plot is created to visualize the actual return vs. the strategy returns.


