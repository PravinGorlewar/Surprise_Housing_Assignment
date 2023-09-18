# Project Name
> Surprise Housing Price Prediction



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
 
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Business Goal 

 You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Metric	            Linear Regression	Ridge Regression	Lasso Regression
R2 Score (Train)	9.562003e-01	    8.935452e-01	    9.325195e-01
R2 Score (Test)	    -3.240123e+22	    8.630473e-01	    8.468941e-01
RSS (Train)	        2.794730e+11	    6.792558e+11	    4.305727e+11
RSS (Test)	        9.132976e+34	    3.860302e+11	    4.315615e+11
MSE (Train)	        1.654463e+04	    2.579312e+04	    2.053574e+04
MSE (Test)	        1.444006e+16	    2.968750e+04	    3.138949e+04


 Ridge Model will be the best fit model for predicting housing pricess. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook
- Python 3.10.9 | packaged by Anaconda, Inc
- Python library used
    warnings
    numpy
    pandas
    sklearn
    statsmodels
    matplotlib
    seaborn
- Kernel Infomation
Python 3.10.9 | packaged by Anaconda, Inc. | (main, Mar  1 2023, 18:18:15) [MSC v.1916 64 bit (AMD64)]
Type 'copyright', 'credits' or 'license' for more information
IPython 8.10.0 -- An enhanced Interactive Python. Type '?' for help. 


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Referances:
https://www.geeksforgeeks.org/
https://stackoverflow.com/



## Contact
Created by [PrvinGorlewar] - feel free to contact me! pravin.gorlewar@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->