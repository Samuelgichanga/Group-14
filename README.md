
# Time Series Analysis of Gasoline Weekly Retail Prices

By: Annette Kalekye|Eric Njeru | Samuel Gichanga

## Project Overview

The gasoline service providers desire to invest in York City and the cities around New York, but they are not sure which city to invest in and which not to. This project aims to uncover patterns in historical pricing data for gasoline business stakeholders. To assist in strategic decision-making, optimize pricing strategies for energy-related businesses, and contribute to effective policy making related to energy efficiency, sustainability, and economic stability in gasoline prices.


### Business Problem

+  Gasoline service providers aim to optimize their investments and expand their services in cities with promising opportunities. To make informed decisions, it is crucial to identify the most lucrative city for investment and understand the trends in gasoline prices across different cities. The business problem encompasses selecting the optimal location for expansion and gaining insights into the variations and patterns of gasoline prices over time.

+ Key Question:

Which is the best cities for gasoline service providers to invest in?


### The Data

The data was collected from the American Automobile Association (AAA) Daily Fuel Gauge Report, the data spans from October 2007 to November 2023, with varying start dates for some regions.

We utilized data from these columns: New York State, Albany, Binghamton, Buffalo, Nassau, New York City, Rochester, Syracuse, Utica

## Modeling

+ We employed the ARIMA model to fit our data, which includes training the model on historical time series data to capture patterns and relationships.
Our ARIMA model performed relatively well with mean squared errors of as low as 0.0233 t0 0.0311 across the cities as shown below
  


   City:      New york state  ,               mse:    0.0251  ,              Best order:   (2,0,2)
     
   City:      Albany  ,                       mse:    0.0255  ,              Best order:   (2,0,2)

   City:      Binghamtom   ,                  mse:    0.0259   ,             Best order:   (2,0,2)

   City:     Buffalo    ,                    mse:    0.0244   ,             Best order:    (2,0,0)

   City:     Nassau    ,                     mse:    0.0311    ,           Best order:    (2,0,2)
     
   City:     New york city   ,               mse:    0.0281    ,           Best order:     (2,0,2)

   City:     Rochester    ,                  mse:    0.0236    ,           Best order:     (2,0,2)

   City:     Syracuse    ,                   mse:   0.0265      ,          Best order:    (2,0,1)

   City:    Utica       ,                   mse:   0.0233       ,         Best order:     (2,0,2)
     
   
## Conclusion
To answer the Business question, the gasoline service providers could invest in any city because the trends are the same and even the forecasted future trends are the same for all cities there is no advantage of investing in one city over the other.

The model predictions were useful in this context:

+ Consistency in Gasoline Price Trends: The analysis reveals a consistent and parallel trend in gasoline prices across all cities under consideration. This suggests that external factors affecting gasoline prices  have a uniform impact on retail prices in these cities.

+ We observed Common Influencing Factors: The observed similarity in trends implies that there are factors influencing gasoline prices that affect all cities simultaneously.
  
+ Global Market Dynamics: The uniform trend in gasoline prices is indicative of the interconnectedness of global markets. Fluctuations in international oil prices and market dynamics seem to propagate uniformly, impacting the retail prices of gasoline in various cities.

+ Economic Implications: Understanding the consistent trend in gasoline prices across cities can have implications for economic forecasting and policy planning. Decision-makers can use this information to anticipate the potential effects of global economic changes on local economies and consumer behavior related to fuel consumption.

+ Consumer Behavior and Sensitivity: The uniformity in gasoline price trends reflects a shared sensitivity among consumers in different cities to changes in fuel costs. This insight could be valuable for businesses, policymakers, and researchers studying consumer behavior and preferences related to energy expenditures.

## Recommendations

This analysis leads to these recommendations:
+ Future Research Directions: The discovery of a common trend in gasoline prices across cities opens avenues for future research to explore the specific factors driving this consistency in fuel prices.

+ Data Quality:The consistency in trends raises questions about the generalizability of the model and the quality of the data used. Further investigation into the robustness of the model and potential outliers or anomalies in the dataset may provide additional insights.
