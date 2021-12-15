# Bike Rental Prediction

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, 
and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The company wants to know:

• Which variables are significant in predicting the demand for shared bikes.

• How well those variables describe the bike demands.

The goal is to model the demand for shared bikes with the available independent variables.
It will be used by the management to understand how exactly the demands vary with different features. 
They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The goal is to model the demand for shared bikes with the available independent variables.

- Reading and Understanding Data.
- Visualising and Preparing the Data.
- Splitting the data into Train and Test Sets
- Feature Scaling
- Model Building
- Residual Analysis of Train Sets
- Making predictions using final model
- Model Evaluation

## Conclusions

The top 3 features contributing significantly towards explaining the demand of the shared bikes are:
 
- Temperature (temp) - A coefficient value of ‘0.4910’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.4910 units.
- Weather Situation(weathersit_Light Snow & Rain) - A coefficient value of ‘-0.2842’ indicated that, a unit increase in weathersit_Light Snow & Rain variable decreases the bike hire numbers by 0.2842 units.
- Year (yr) - A coefficient value of ‘0.2336’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.2336 units.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Language : Python 3.8.8
- Notebook : Jupyter notebook 6.3.0
- Library  : Numpy, Pandas, matplotlib, sklearn, statsmodels and seaborn

## Acknowledgements
The goal is to model the demand for shared bikes with the available independent variables. 
It will be used by the management to understand how exactly the demands vary with different features. 
They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Contact
Created by [@KrishnamoorthyVK] - feel free to contact me!
