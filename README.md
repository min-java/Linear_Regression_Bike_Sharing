## Linear Regression Assignment

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Info]
  The project takes input as CSV file with below structure
  instant         int64
  dteday         object
  season          int64
  yr              int64
  mnth            int64
  holiday         int64
  weekday         int64
  workingday      int64
  weathersit      int64
  temp          float64
  atemp         float64
  hum           float64
  windspeed     float64
  casual          int64
  registered      int64
  cnt             int64

* [Technologies Used]
  Python 3.10.11
  Pandas version - 1.5.3
  numpy version - 1.22.4
  seaborn version - 0.12.2 
  statsmodel version - 0.13.5
  sklearn version - 1.2.2

* [Conclusions]
  Linear Regression Model has been trained on 'yr', 'workingday', 'temp', 'hum', 'windspeed',
       'ratio_casual_registered', 'mnth__8', 'mnth__9', 'season__2',
       'season__4', 'weekday__6', 'weathersit__2', 'weathersit__3'
  with R^2 value 0.81

* [Acknowledgements]
  Upgrad instructors and staff

## Contact
Created by [minakshi.garg] - feel free to contact me!
