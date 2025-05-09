# COMED_power

## Overview
This project was created for the class DATA 6330 at MTSU during Spring 2025. The goal was to predict how much power the Chicago area (COMED) would require given weather, population, and time data. 

## Data Sources
* Chicago population: https://www.macrotrends.net/global-metrics/cities/22956/chicago/population 
* Chicago weather: https://www.ncei.noaa.gov/access/search/data-search/global-hourly?pageNum=1&startDate=2011-01-01T00:00:00&endDate=2017-12-31T23:59:59&bbox=42.010,-87.934,41.950,-87.874&pageSize=10&dataTypes=TMP&dataTypes=RH1&dataTypes=CIG&dataTypes=VIS&dataTypes=WND&dataTypes=OC1&dataTypes=MA1 
* Chicago (COMED) energy: https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption?select=COMED_hourly.csv 

## Results
The final model has a 98.5% accuracy using a gradient boosting regression model
