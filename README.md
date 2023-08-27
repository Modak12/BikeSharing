# BikeSharing
> To predict the demand for the shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

The company wants to know:
- Which variables are significant in predicting the demand for shared bikes
- How well those variables describe the bike demands

Dataset used here is : day.csv

## Conclusions
Based on the coefficients we can say, below are the list of important variables in the order of there importance:
- temp : 0.547727 indicates that temperature has a significant impact on bookings
- light_rain : -0.289291 indicates that snow & rain are negatively impacting the bookings
- yr : 0.232913 indicates that the bookings of bike has increased over year
- windspeed : -0.154257 indicates that bike bookings decreases with increase in windspeed
- winter : 0.132127 indicates that bike booking is preferrable during winter season

Inference
- We can say that with increase in temperature and good weather condition positively affects the bike booking.
- We can dock more bikes based on the weather forcast( Clear > Misty > Rainy)
- Summer & Winters have more bike bookings, so we can promote, advertise more during these seasons
- Month september and day saturday also shows positive relationship with bike bookings
- There is a increase in bike bookings over the year. Once the lockdown opens, we can see the increase in bookings as well
- We can offer discounts may be to increase the bike bookings during spring season, cloudy and rainy weather etc.

We can see that the equation of our best fitted line is:
$ cnt = (0.547727 temp) + (0.232913 yr) + (0.132127 winter) + (0.099248 Sep) + (0.086798 summer) + (0.059118 Sat) + (0.047862 workingday) - (0.289291 light_rain) - (0.154257 windspeed) - (0.057089 holiday) - (0.081844 * misty)


## Technologies Used
- python 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was a problem statement given by IIIT-B for the cohort course of ML-AI.


## Contact
Created by [@Modak12] - feel free to contact me!
