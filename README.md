# Machine Learning Practice: Financial Prediction using Linear Models, KNN, and Decision Trees

## Objective

The aim of this practice is to apply the concepts learned about constructing linear models, K-Nearest Neighbors (KNN), and decision trees to a dynamic prediction problem in a financial context. The student should be able to implement these Machine Learning models in Python, including the associated metrics and other analyses.

## Approach

This practice proposes the use and analysis of a Machine Learning model and illustrates how some Machine Learning models can be used in dynamic modeling problems, contextualizing the concepts seen. The student is also expected to develop a critical vision of the model.

The problem is a dynamic prediction problem. The student should use data from the S&P500 from Yahoo Finance:

[S&P500 Historical Prices](http://finance.yahoo.com/q/hp?s=%5EGSPC+Historical+Prices)

The student should use the quotations from the first day after January 1, 2021 (for example, January 4) to February 28, 2023, or the last day of February available before that date.

Once the quotations are obtained, the student must transform them into returns (yields) by taking the difference (from the second available day) of prices and dividing it by the previous price:

From these returns, the student should construct a matrix of dependent (rt) and independent variables considering the returns of the previous five days in addition to a vector of ones (1, rt-1,….,r t-5). It is only possible to construct this matrix from the SIXTH observation of returns (or SEVENTH of prices), discarding the incomplete rows.

## Code

The code for this practice is available in this repository. We invite you to explore it and to make any questions or suggestions you may have.

## Results

The results of our practice will be presented in the form of graphs and analysis in the corresponding notebook. This will include the evaluation of the fit quality and predictive ability of our Machine Learning model.

We hope you find this practice interesting and that it helps you better understand how Machine Learning models can be applied to real prediction problems in the field of finance.
