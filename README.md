# Advanced_Regression_Housing_Price
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house.

* Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
We need to analyze how ridge & lasso preven the overfit & underfit of the model & it helps to predict the Most Important Feature which is the predictor variable for sale Price of the house
- Dataset : train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Conclusions
Ridge & lasso helps to prevent overfit & underfit .
* Optimal Lambda for Ridge Regression : 5
* Optimal Lambda for Lasso Regression : 0.0001.
<h2>Model Outcome Summary</h2>
After compairing linear regression , ridge and lasso regression the below mentioned Features are considered best explaining the Dataset.

* MiscVal : $Value of miscellaneous feature
* BsmtHalfBath : Basement half bathrooms
* LowQualFinSF : Low quality finished square feet (all floors)
* BsmtFullBath : Basement full bathrooms
* HalfBath : Half baths above grade

## Technologies Used
- Python Libraries - Numpy, Pandas
- Data Visualization Libraries - Matplotlib and Seaborne
- Linear Regression model libraries - Sklearn, Statsmodels



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

