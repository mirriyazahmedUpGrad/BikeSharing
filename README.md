# Project Name
Bike Sharing 

Problem Statement

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know: • Which variables are significant in predicting the demand for shared bikes. • How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

Business Goal: You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. .

Solution Approach
1. Understanding/visualizing, evaluating and preparing data (using appropriate categorical variables and dummy variables; with modification where needed); EDA principles applied
2. Building the model
a. splitting the data into training and test data sets
b. rescaling the features if/as needed
c. feature selection using R-Sqaure and VIF values (RFE and Statsmodel combination to be used)
3. Perform residual analysis and predictions

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information

Below is the approach followed for arriving and evaluating the linear regression model

1.	Getting data ready and understanding data
a.	Reading, understanding/visualizing
b.	Checking and cleaning up data (missing values, nulls, etc.)
c.	Evaluating and preparing data (dropping redundant cols, using appropriate categorical variables and dummy variables; with modification where needed); 
d.	Applying EDA principles (finding relation between data using univariate, bivariate analysis)
e.	
2.	Building the model
a.	Deciding to use RFE and/or manual model building
b.	splitting the data into training and test data sets
c.	rescaling the features if/as needed
d.	feature selection using R-Sqaure and VIF values (RFE and Statsmodel combination to be used)
3.	Perform residual analysis and predictions using test data
4.	Evaluating the model




## Conclusions
Based on the values of R-Square and adjusted R-Square for the training and test data and validation done based on the residual errors and linear relation between the y_test and y_pred values, it was concluded that the model arrived is acceptable.

Model is cnt=0.207455-0.077871*Jan+0.074450*Sep+0.064373*Sat-0.254779*Light-0.053681*Misty+0.096517*Winter+0.231452*yr+0.055762*workingday+0.533595*temp-0.132436*hum-0.177242*windspeed



## Contact
Created by [@mirriyazahmedUpGrad] - feel free to contact me!


