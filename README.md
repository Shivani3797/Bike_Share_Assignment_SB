# Project Name
Bike Sharing Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
### Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
1. Which variables are significant in predicting the demand for shared bikes?
2. How well do those variables describe the bike demands?
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

### Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

### Data 
Data used here is given by Upgrad but is also publicly available at "https://www.kaggle.com/datasets/santhraul/boom-bike-dataset?select=bike_sharing_data.csv".


## Conclusions
- Bike rentals were more in the year 2019 compared to 2018.
- Bike rentals increased during good weather, in the fall season, particularly in September, and were more popular on working days.
- Winter, Temperature, Summer, humidity, wind speed, September, year, holiday, and Sunday are the most significant variables to predict the demand for share bikes.
- The equation for the best-fit line can be given as,
   ##### cnt= 4491+997.2873 x yr-124.3817 x holiday+1170.3808 x temp-432.1850 x hum-347.497 x windspeed+342.3 x summer+528.6401 x winter+239.2852 x sep -113.0042 x sun
- For the training data, the R² score is 0.810 and the adjusted R² score is 0.800. For the test data, the mean squared error is 837.8657520624623, and both the R² and adjusted R² scores are 0.8. These metrics suggest that the predicted model performs fairly well.

## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Seaborn - version 0.12.2
- Statsmodels - version 0.14.0
- Scikit-Learn - version 1.3.0

## Acknowledgement
UpGrad tutorials on Linear Regression on the learning platform.
Also referred Akash Kriplani and Chandrakant Shinde's GitHub.


## Contact
Created by [@Shivani3797] - feel free to contact me!
