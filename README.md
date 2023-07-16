# Bike-Sharing-Linear-Regression
Building a multiple linear regression model for the prediction of demand for shared bikes. 

## Problem Statement
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

## Business Goal
It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2

## Conclusion
On analysing data, it was observed that, the linear regression model was able to predict bike demand precisely with an R2 Score of more than 80%

Significant variables to predict the demand for shared bikes: 
- temp
- windspeed
- Season (Spring, Summer, Winter)
- Months(September)
- Year (2019)
- weathersit( Light Snow, Mist + Cloudy)
