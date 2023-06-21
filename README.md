# HousePriceCaseStudy
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
Problem statement:

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Steps followed](#Steps)
* [Final model from linear regression](#final-model-from-linear-regression)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem statement
> You are required to model the price of houses with the available independent variables. 
> This model will then be used by the management to understand how exactly the prices vary with the variables. 
> They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
> Further, the model will be a good way for management to understand the pricing dynamics of a new market


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps
Steps:
* Data understanding and exploration
>> Initial report using sweetviz before doing any data changes
* Data cleaning
>> * Imputation of missing values.
>> Drop unwanted columns.
>> * Handle the formate.
>> * Adjust datatype.
* After clean up: Data understanding and exploration
>> * Univariate analysis after imputation
>> >> * univariate analysis of numerical variables
>> >> * univariate analysis of categorical variables
>> * Bivariate analysis
>> >> * Heatmap
>> >> * SalePrice vs numeric variables - pairplot
>> >> * SalePrice vs categorical variable
* Data preparation
>> * Ordinal encoding and Dummy encoding
* Model building and evaluation
>> * Linear regression with unregularised
>> * Regularisation: Linear regression with Ridge regression
>> * Regularisation: Linear regression with Lasso regression
* Compare linear regression without regularization and other regularized methods: Ridge and Lasso
> 
## Final model from linear regression
- r2_score_test
- > linear regression without regularization =	-1.945387e+23
-  > Ridge regression =	0.893687 
-  > Lasso regression =	0.877688
- rss_test:
-  > linear regression without regularization =	9.779682e+24
-  > Ridge regression =	5.344478
-  > Lasso regression = 6.148776
-  mse_test			
-  > linear regression without regularization =	3.349206e+22
-  > Ridge regression =	0.018303
-  > Lasso regression = 0.021057

## Technologies Used
- Jupyter notebook - version 6.4.12
- Python - version 3.10.0
- Pandas - version 2.0
- Numpy - version 1.24.2
- Matplotlib.pyplot - version - 3.7.1
- seaborn - version - 0.12.2
- statsmodel - version - 0.14.0
- sklearn - version - 1.2.2

## Acknowledgements
- Upgrad
- Google in general


## Contact
Created by [@suryabandari247] - feel free to contact me!
