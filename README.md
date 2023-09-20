# Project Name
Linear Regression Assignment - Bike Sharing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.
- It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market for "Boom bikes"
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
- Dataset that is being used for Bike Sharing dataset is day.csv, 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1
   Data Understanding/Exploration¶
    In this section, we have analysed the given dataset w.r.to it's structure. In the process, we have changed the data types of few columns and also changed some of the values based 
    on Data Dictionary.
- Conclusion 2
    Data Visualization:
     In this section, we have looked at the actual data content.We plotted few distribution plots and a correleation Matrix and heatmap for numerical varibales. We also removed one of 
     the features "atemp" as it was highly correlated with the another varibales "temp".
- Conclusion 3
   Data Preparation:
    The main task done in this section are:
    create the respective dummy variables
    delete the irrelevant data
- Conclusion 4
   Model Building and Evaluation:
    In this section, we build our first model considering all the variables and then we made an informed choice based on VIF and p-values and finally made our baseline model with 7 
    variables. We also plotted the error term to check if they are normally distributed. Our regression line also looks pretty clustered around the central line.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.3
- sklearn - version 1.2.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by... Boom Bike Sharing Company


## Contact
Created by [@somyakhare10] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
