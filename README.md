#  Advanced Regression Assignment 
# Problem statement 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.


The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
Problem Statement
Data understanding
Create Dummy Varibales
Plotting heatmap to check the corelation between varables
Let us check the distribution of our target variable before scaling and Splitting
Prepairing Data For Modeling
Rescalling The Numeric Factors
Training The Model
RFE- Recursive Feature Elimination
Building model using statsmodel, for the detailed statistics
Rebuild the model without GarageType_NA
Residual analysis of Train Data
Evaluate R2 of Train model
Calculate r2 score of Test mode
Final evalution
Ridge Regression
Lasso Regression
Lets observe the changes in the coefficients after regularization
The company wants to know:



<!-- You can include any other section that is pertinent to your problem -->

## General Information

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


# Business Goal 

 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Conclusions
-Final evalution
No of Variables = 21

VIF < 5
p-value < 0.05
r2 score for Train Data set model = 0.80
r2 score for Test Data set model = 0.82


Coeff values are deceresing as alpha will increase.r2_score of train data is also drop from .839 to 0.835

As alpha value increse But r2score is also dropped by .839 to .833

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3.0
- pandas 
- numpy 
- matplotlib 
- seaborn 
- sklearn.linear_model 
-  LinearRegression, Ridge, Lasso
- GridSearchCV
- statsmodels 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by IIIT banglore assigment
- upgrad
- This project was based on assignment form upgrad

## Contact
Created by [@karansbisht] - feel free to contact me!

