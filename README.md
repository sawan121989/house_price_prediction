# Project Name

### House Price Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
**Business Objective** :
An US based company wants to expand their business to Australian Market. They want to understand the factors impacting the price of houses so they can buy them below their actual price and sell at higher price. Using the features they want to identify the potential properties they should buy.

**Business Problem** : The company wants to understand :

* Which features contribute towards price of Houses.
* How well those features explain the price

**Business Goal** : Need to create a model that explains the price of the houses using idependent variable availble in dataset.
The model will be used by management to understand how price varies with respect to those variables. Accordingly they can form their strategies to get high returns.


## Technologies Used
- python3
- Jupyter Notebook
- python libraries - pandas, numpy, seaborn, matplotlib, sklearn


## Conclusions
- From EDA we found Numerical variables GrLivArea, GarageArea, TotalBsmtSF, 1stFlrSF, TotRmsAbvGrd and Categorical variables OverallQual, Neighborhood, GarageCars, ExterQual, BsmtQual have high linear behaviour with SalePrice

- Total of 272 features were selected at the end of EDA

- Models for Linear Regression , Ridge and Lasso were creted with all the features and coefficients and results were compared

- The error term for all the model seems to follow Normal distribution with mean 0

- The best **Alpha value for Ridge was obtained as 5 and for Lasso it was obtained as 0.0001**

- Upon final comparison of results, it was found that Lasso regression gave slightly better results with minumum difference in train and test score. Also Lasso regression helped to remove some features and finally selected 116 features which makes it less complex than other models.

- Based on results, **Lasso Model can be finally selected** as best among the 3

- Top 10 features selected by Lasso Model - **GrLivArea, OverallQual_Very Excellent, TotalBsmtSF, OverallQual_Excellent, PoolArea, Neighborhood_StoneBr, BsmtFinSF1, Neighborhood_NoRidge, OverallCond_Excellent, Neighborhood_Crawfor**


## Acknowledgements
- This project was inspired by Course in ML and AI from IIITB and Upgrad


## Contact
Created by [@sawan121989] - feel free to contact me!


