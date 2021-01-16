# Project 2: Ames Housing Sale Price Prediction

## Problem Statement

Century 21 Real Estate LLC as consultants is looking to improve their digital brokerage services, by providing recommendations to house sellers on potential value of their house and what they could do to increase the value of their house. Consequently, Century 21 can benefit from higher sale prices and transactions from house sellers and investors.

This report seeks to provide recommendations on the features that are most influential on the sale price of the house through exploratory analysis on the comprehensive housing dataset from the city of Ames in Iowa, USA (2006 -2010), and development of a regression model that seeks to be able to provide good prediction accuracy with good generalizability based on the features which have most influential impact on sale price.

## Executive Summary

Four regression learning algorithms were evaluated in their predictive performance on housing sale price in Ames, USA. The ElasticNet regression model had the best predictive performance with a R-square of 91.9% and was able to identify the top features which impact sale price of houses in Ames.

**Overall quality** of the house in terms of material and finish, and above ground **living area and basement area (sq ft)** appear to add the most value to a home. Conversely, the **age of the property** and **Mansard roof style** appear to hurt the value of a home the most.

For home owners, they could consider the following to increase the value of their homes:

- renovating or remodelling the interior and exterior house to improve overall finish quality
- refurbishing the kitchen to improve its quality
- having a quality fireplace which would come in handy during winter season

For someone looking to buy a house for investment, they could consider looking at houses in the **Northridge Hts and Stone Brook neighbourhoods** which fetch higher sale value compared to the other neighbourhoods. In addition, houses located within **proximity of green belt, parks or amenities etc, and hilly terrain** would fetch higher prices as well.

To make the prediction model applicability more universal, the model could be revised to remove those specific features which only apply to Ames, e.g. neighbourhoods or engineering more universal features from the data. The model could also be enriched by collecting data from other cities in the same timeframe so that comparative analysis could be made.

### Contents:
- [Data Cleaning](./code/Ames_Housing_Sale_Price_Prediction_v2.ipynb#Data-Cleaning)
- [Exploratory Data Analysis](./code/Ames_Housing_Sale_Price_Prediction_v2.ipynb#Exploratory-Data-Analysis)
- [Pre-processing & Feature Engineering](./code/Ames_Housing_Sale_Price_Prediction_v2.ipynb#Pre-processing-&-Feature-Engineering)
- [Modelling](./code/Ames_Housing_Sale_Price_Prediction_v2.ipynb#Modelling)
- [Kaggle Submission](./code/Ames_Housing_Sale_Price_Prediction_v2.ipynb#Kaggle-Submission)
- [Conclusion & Recommendations](./code/Ames_Housing_Sale_Price_Prediction_v2.ipynb#Conclusion-&-Recommendations)

## Data Dictionary

The data description for the Ames housing dataset can be found [here](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)
 
