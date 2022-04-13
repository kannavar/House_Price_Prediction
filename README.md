# House_Price_Prediction
Housing Price Prediction using  Linear regression with regularization techniques


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Problem Statement

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

### Analytical Goal

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and How well those variables describe the price of a house.

Also determine the optimal value of lambda for ridge and lasso regression.

### Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- According to the Ridge regression the variables "GrLivArea , RoofMatl_WdShngl , Neighborhood_StoneBr, Functional_Typ, 2ndFlrSF, Neighborhood_NridgHt, OverallQual, Neighborhood_NoRidge, SaleType_New , TotalBsmtSF" are the top 10 factors that influence the Sale price of the house.
- According to the Lasso Regression analysis  the variables "RoofMatl_WdShngl, Neighborhood_StoneBr, GrLivArea, Neighborhood_NridgHt, Neighborhood_NoRidge, SaleType_New, Functional_Typ, Neighborhood_Crawfor, Foundation_Slab, Exterior1st_BrkFace" form the important factors for SalePrice prediction of a house.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- MatplotLib
- Seaborn
- SkLearn 
- StatsModel 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@kannavar] - feel free to contact me!
