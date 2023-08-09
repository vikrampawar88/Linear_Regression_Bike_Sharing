# Linear Regression to understand factors affecting demand of Bike Sharing
> In this project we are focused on building the linear regression model to understand the factors affecting demand for shared bikes in American market for BoomBikes to better cater to people'e demand of shared bikes after end of quarantine situation across nation due to Covid-19 so they can stand out from other service providers and make huge profits.


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Objective](#business-objective)
* [Solution Approach](#analysis-approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Team](#team)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


Boombikes want to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

## Business Objective
To model the demand for shared bikes with the available independent variables. 
It will be used by the BoomBikes management to understand how exactly the demands vary with different features on which they can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
Further, the model will be a good way for management to understand the demand dynamics of a new market.

- Data Set : 
Is fetched from publication
[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.


## Solution Approach
1. Reading and Understanding the Data
2. Visualising the Data
3. Data Preparation for modelling
4. Splitting the Data into Training and Testing Sets
5. Building a linear model
6. Residual Analysis of the train data
7. Making Predictions Using the Final Mode
8. Model Evaluation

## Conclusions

Final recommended variables significant in predicting the demand for shared bikes

<br/>

__temp :__ Demand is postively related with temperature
<br/>
__yr :__ Year, yearwise there is growth in demand
<br/>
__sep :__ Demand seems to be more during september month
<br/>
__winter :__ Demand is postively related with winter season
<br/>
__summer :__ Demand is postively related with summer season
<br/>
__light_snow_rain :__ Demand is negatively related with weathersit being Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
<br/>
__windspeed :__ Demand is negatively related with wind speed
<br/>
__holiday :__ Demand is negatively related with holiday, seems people wish to spend time with family
<br/>
__misty :__ Demand is negatively related with weathersit being Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
<br/>
__spring :__ Demand is negatively related with winter season
<br/>
__sep :__ Demand seems to be more during september month
<br/>

## Technologies Used
- Python - Version 3.9.13
- numpy - Version 1.21.5
- pandas - Version 1.4.4
- matplotlib - Version 3.5.2
- seaborn - Version 0.11.2
- statsmodels - Version 0.13.2
- scikit-learn - Version 1.0.2
- Jupyter Notebook - Version 6.4.12
- Anaconda - Version 2.3.2

## Acknowledgements

## Team
[Vikram Pawar](https://www.linkedin.com/in/vikrampawar88/)


## Contact
Created by [@vikrampawar88] - feel free to contact me!



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
