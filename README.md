# Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In this analysis, EDA is used to understand how consumer  attributes and loan attributes influence the tendency of default.
- As described in the live session notes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

Aim of this assigment is to use Multiple Linear Regression to find the most impacting features for bike demand such that the company can plan to work on those features to increse the bike rentals. 


## Technologies Used
- Python - version 3.10.9
- IPython - version 8.10.0
- pandas - version 1.5.3
- numpy - version 1.23.5
- seaborn - version 0.12.2
- jupyter notebook - version 6.5.2
- sklearn 
- 


## Conclusions
The categorical variable, weathersit is significant. Especially the values 1 (Clear, Few clouds, Partly 
cloudy, Partly cloudy) and 3 (Light Snow, Light Rain + Thunderstorm + ScaƩered clouds, Light Rain + 
Scattered clouds) has negatve correlation on the dependent variable, cnt. 
The categorical variable, mnth is significant. While month Sep has a posiƟve correlaƟon with cnt, the 
months, dec, jan and nov have negaƟve correlation with cnt. 
The categorical variable, weekday is significant with only Sat has posiƟve correlaƟon with cnt. 

Working day with coeff value of 0.0570, yr with the coeff value of 0.2457 and light rain (dummy 
variable of weathersit) with coeff value of -0.3207 are the top 3 features contribuƟng significantly 
towards explaining the demand of the shared bikes. 

## Acknowledgements
- This project was based on the learnings from Linear Regression module of ML C54 EPGP program by IIIT Bangalore and upGrad


## Contact
Created by [@githubusername] - feel free to contact me!


