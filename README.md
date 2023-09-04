# London Bike Hire Data Regression Analysis
**Author**: [Raye Yoo](mailto:y100265@gmail.com)

![tfl](/santander-cycle-hire.jpg)

## Project Overview

This data analysis project provides the most impactful features to contribute to the number of bike hires in London through multiple regression analysis. The data shows that the hours (trip starting), weather and temperature affect the bike
hire demand significantly. Transport for London (“TFL”) can use this data to plan the bike supply to improve its business profit model.

## The Data
#### Data source: London bike sharing dataset, kaggle
* The number of bikes hired every hour in London (00:00 4th Jan 2015 – 23:00 3rd Jan 2017)
* Historical data for bike sharing in London 'Powered by TfL Open Data’
* A merged dataset from https://cycling.data.tfl.gov.uk/, freemeteo.com, and https://www.gov.uk/bank-holidays

#### Understanding data
* timestamp: Timestamp field for grouping the data by hour
* cnt : The count of a new bike hires
* t1 : Official temperature in Celsius
* t2 : “Feels like” temperature in Celsius
* hum : Humidity in percentage
* wind_speed : Wind speed in km/h
* weather_code : Category of the weather
* is_holiday: Boolean field - 1 holiday / 0 non-holiday
* is_weekend : Boolean field - 1 weekend / 0 weekdays
* season - Category field meteorological seasons: 0-spring; 1-summer; 2-fall; 3-winter

#### Data Analysis Approach
Multiple Regression Analysis

## Key Points
The most impactful feature is the trip starting time (hour), the commuting hours are directly related to the number of bike hire. Also, bad weather such as rain and snow impacts the bike hire demands negatively.

## Conclusion

* Obtain the location data analysis: To be able to predict not only the demand but also effective bike relocations to increase bike hire. This will also help to supply the right number of bikes to be hired from the right places
* Adopt new types of vehicles and demand: E-bikes & scooters were released in late 2020 in London, we should look at the recent data to see the trends to predict more accurate customer demands

## For more details
* [Presentation](https://github.com/Rayeyoo1/london_bike_data_modelling/blob/main/Notebook.pdf)
* [Jupyter Notebook](https://github.com/Rayeyoo1/london_bike_data_modelling/blob/main/london_bike_prediction_modelling.ipynb)
* [Data Source](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)


