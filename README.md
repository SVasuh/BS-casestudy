# Bike Sharing Case Study

A bike-sharing system allows users to rent bikes from others for short periods of time for a fee or free. Many bike share programs allow customers to check out bikes from "docks," which are often computerized sites where users enter payment information and the system unlocks the bike. Following that, you may return this bike to any other dock in the system.

BoomBikes, a US bike-sharing company, has recently seen significant revenue declines as a result of the current Corona pandemic. In today's market, the company is struggling to stay afloat. As a result, it has chosen to develop a strategic business plan in order to increase income.

BoomBikes hopes to better understand the demand for shared bikes once the existing quarantine situation caused by Covid-19 ends across the country. They planned this to position themselves to meet the demands of the people if the situation improves overall, to differentiate themselves from other service providers, and to make large profits.

## Study By
- Vasudha Srinivasaiah

## Table of Contents
* Problem Statement
* Business Understanding
* General Info
* Conclusions
* Technologies Used
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->
## Problem Statement

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Business Understanding

Required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## General Information

- Steps for EDA :
- Data Understanding
- Data Preperation 
- Data Visualisation
- Model Building
- Model Evaluation
- Prediction
- Prediction Evaluation
- Conclusion
- Data Set : Bike Sharing Rentals 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Model Evaluation resulted in 
- Test data R-Squared : 80.38
- Train data R-Squared : 83.27

- Test data adjusted R-Squared : 79.44
- Train data adjusted R-Squared : 82.94

Based on the R-Squared and adj R-Squared values of the train and test datasets, we may deduce that the variables mentioned above account for about 80% of the demand for bicycles.

    The variables' coefficients explain the factors influencing the demand for bikes.

    According to the final model, the below predictor variables influences bike booking :
        Temperature (temp)
        Months September
        Year
        Windspeed
        Seaons Summer, Winter, Spring
        If its a holiday
        If the weather is Clear

In order to maximize demand, it is advised that these aspects be given the utmost consideration throughout planning.



## Technologies Used

- Pandas - 2.0.3
- Numpy - 1.24.3
- Matplotlib - 3.7.2
- Seaborn - 0.12.2
- Plotly - 5.9.0
- scikit-learn - 1.3.0
- statsmodel.api - 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project is individual case study for an online advance course.
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://scikit-learn.org/
- https://www.statsmodels.org/



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
