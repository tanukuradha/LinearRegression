
# Project Name
Demand for shared Bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project focuses to model the demand for shared bikes with the available independent variables.
- It will be used by the management to understand how exactly the demands vary with different features. 
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the demand dynamics of a new market.
- The dataset used in this project is the day.csv provided for our case study.

## Conclusions

Strong positive or negative correlations are indicated by darker colours of blue or red, respectively, in the heatmap that displays the correlation between the variables. Some factors that are related to forecasting the demand for shared bikes (variable cnt) are as follows:

-Important Factors Year (yr):

significant positive association (0.57) with cnt.
shows a discernible rise in the demand for bikes over time.

-Temperature (temp and atemp):

There is a high positive association between both factors and cnt (0.63 each).
In general, more people ride bikes in warmer weather.

-Season (season):

0.4 indicates a somewhat positive connection with cnt.
indicates that some seasons, such as spring or summer, have more demand.

-Windspeed (windspeed):

cnt has a weakly negative correlation (-0.24).
suggests that strong wind speeds could marginally lower consumption.

-The current weather conditions (weathersit):

cnt has a moderately negative correlation (-0.3).
Unfavourable weather conditions, such as rain or snow


## Technologies Used
- Python: 3.9.19
- pandas: 1.4.0
- seaborn: 0.11.2
- matplotlib: 3.5.1

## Acknowledgements
- The dataset used in this project was sourced from a Upgrad.

## Contact
Created by @tanukuradha - feel free to contact me!
