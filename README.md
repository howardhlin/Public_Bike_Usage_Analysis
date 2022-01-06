# Public_Bike_Usage_Analysis

The purpose of this system is to support decision making process for Chicago Divvy Bike company including resource and infrastructure planning. By extracting, organizing, analyzing and visualizing with a variety of platforms (MySQL, Tableau, Excel, Open Refine, Kepler.gl), my teammates and I aim to identify the factors contributing to the usage of Divvy Bike in Chicago.


The data includes the following:
1. Divvy trips (https://data.cityofchicago.org/Transportation/Divvy-Trips/fg6s-gzvg)
2. Divvy Stations (https://data.cityofchicago.org/Transportation/Divvy-Bicycle-Stations/bbyy-e7gq/data)
3. Chicago Weather (https://www.ncdc.noaa.gov/cdo-web/)
4. Chicago Traffic Tracker (https://data.cityofchicago.org/Transportation/Chicago-Traffic-Tracker-Congestion-Estimates-by-Re/t2qc-9pjd)
5. Covid-19 Cases (https://dph.illinois.gov/covid19/data.html)


This repository includes the following sections: 

1. Data cleaning and processing: 
- For 5 dim table (traffic/region/covid/bike station/weather) and 1 fact table (bike trips)
- Include scripts in Jupyter notebook and cleaned data.

2. DDL DML SQL query:
- Include two parts: “divvybikeDDL” is for building schema “divvybike” to import clean data. “divvybike_snowflakeDDL” and “ divvybike_snowflakeDML” are for building OLAP database “divvybike_snowflake”.

3. BI process
- Include two parts: Kepler.gl and Tableau. (Please use Chrome to open html file)

4. Presentation slides


Time series models for forecasting Divvy Bike future weekly usage, please refer to this repository: https://github.com/howardhlin/Public_Usage_Time_Series_Analysis
