# Forecasting analysis of beer&burger sales. 
This notebook presents a predictive analysis for BforBirra, examining the relationship between beer and burger sales and weather conditions. The analysis integrates company-provided sales data with open-source weather data, including temperature, humidity, and precipitation, to build a forecasting model and explore potential correlations between weather and sales patterns.


## Overview 
BforBirra provided a historical dataset of daily beer and burger sales, which has been enriched with publicly available weather data. The combined dataset allows us to investigate how environmental factors influence sales and to generate short-term forecasts using machine learning techniques. The ultimate goal is to provide actionable insights for inventory planning, staffing, and marketing strategies.

## Dataset
The dataset contains daily sales observations over approximately one year, totaling 400 entries.
Weather data includes daily average temperature, precipitation, and humidity.
The final dataset merges sales and weather data, ensuring that each sales observation is paired with the corresponding weather conditions.

## Task description
Two distinct analyses have been conducted: the first examines the correlation between burger and beer sales and precipitation levels, while the second analyzes the correlation between burger and beer sales and temperature.

### 1.Data Exploration
Examine the structure of the dataset and identify missing values and outliers.


### 2. Data Preparation and Model Training
Preprocess data, including filling missing weather values, creating month-based categorical features, and splitting the dataset into training and test sets.
Train a Prophet forecasting model, including regressors for month bins and seasonality components (weekly/yearly).

## Repository contents 
-	requirements.txt: Contains the necessary Python modules to be installed to run the code.

## Conclusion
Preliminary analysis and forecast results suggest that:

Burger sales show a consistent upward trend over the year, reflecting overall business growth.

Weekly seasonality is pronounced, with higher sales during weekends.

Temperature and precipitation show weak correlations with sales, indicating that other factors (e.g., weekends, events, promotions) are more influential for demand.

The Prophet model provides a robust short-term forecast and captures seasonal patterns effectively, which can help in inventory planning and marketing strategies.




