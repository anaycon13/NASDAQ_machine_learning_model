# NASDAQ_machine_learning_model
Authors: Thor Mead, Arya Bhansali, and Anay Contractor

We trained a multilinear regression machine learning model to predict NASDAQ movements using alternative data. We first aim to backtest this model, then see if we can extrapolate it for future events. The goal is to see if non-traditional financial data (credit card balances, web traffic, loan delinquencies, consumer price indices, etc.) can be used to create statistically significant models for stock market analysis and prediction. Eventually, we would hope to increase the number of relevant variables, search for new parameters, and strengthen the mathematical and statistical foundations of our model. We have stored all of the raw CSV data in the folder called RawData within this project. We obtained our data from https://fred.stlouisfed.org/.


The multicollinearity.ipynb file contains code for testing multicollinearity in data. This is an important step for training any model as multicollinearity can lead to a reduction in the statistical significance of any results. Although regression models have penalties for multicollinearity, this code is for systematically showing how one can assess multicollinearity between independent variables before chosing a model with all the variables as necessary. The Variance Inflation Factor (VIF) approach allows us to clearly show variable refactoring. 
 
