# Project Name
> A multiple linear regression analysis to predict the demand of a Bike share service in the US and also figure out the factors impacting the demand.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

#### Problem Statement:
BoomBikes(US based bike-sharing company) aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

#### Business Goal:
create a model to understand the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

#### Steps
Data Understanding
Visualization
Data Preparation
Feature scaling/Normalization and test-train split
Model building
Goodness of fit - Normality/Homoscedasticity Check (Linear regrssion Assumption check and Models evaluation)
Making predictions using final model (Check accuracy against Training Data)
Conclusion/Recommendations

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

-  Top 3 contributors :- 
    1.temp - coeff: 0.57 - impacts in a positive way. It it increases, count/demand increases for the bike
    2. yr - coeff: 0.23,  impacts in a positive way. year 2019 contributes more to the demand of bikes.
    3. Light Rain coeff:  -0.21, negatively impacts the demand. When there is Light rain, demand decreases as expected.

-  Winter season is attracting people more to use bikes.
-  In Sep, Oct and Aug the demand is high for the bikes
-  In case of high humidity, wind speed and rain, the demand is low as expected
- Month_July,Mist_or_cloud, windspeed, hum, Light_rain has negative coefficient which shows if weather is bad less users use bike.

#### Recommendations:--
Company need to go creative to increase the demand on the bad weather or summer days. Few suggestions are:--
   a)They can reduce the price maybe slice it by half
   b)Provide rain-coats along with the bike on rainy days
   c)Introduce and provide extra credits points during summer and bad weather days.
   
- Well, we can try to improve this model further:--
  1.By trying to fix hetroscedasticity, a litle hetroscedasticity which is not that bad but can be weighted regrssion. It wll make the coefficients more  precised.
  2.Even a non-linear model can be tried to fit to see if it improves the accuracy.



## Contact
Created by [@abhi-singh-123] - feel free to contact me!

