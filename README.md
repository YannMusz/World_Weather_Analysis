# World_Weather_Analysis

## Overview
The purpose of this project is to collect and analyze weather data of cities across the world to provide travelers with a tool that will give them the opportunity to plan their trips according to the weather conditions

### Resources Used
* **CSV Files:** 
[Weather_Database.csv]( https://github.com/YannMusz/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv), 
[WeatherPy_vacation.csv]( https://github.com/YannMusz/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search/WeatherPy_vacation.csv)
* **Jupyter Notebook Files:**: 
[Weather_Database.ipynb](https://github.com/YannMusz/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), 
[Vacation_Search.ipynb](https://github.com/YannMusz/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search/Vacation_Search.ipynb),
[Vacation_Itinerary.ipynb]( https://github.com/YannMusz/World_Weather_Analysis/blob/main/Vacation_Itenary/Vacation_Itinerary/Vacation_Itinerary.ipynb)

## Weather Database
2,000 latitudes and longitudes were generated, API calls were done on current weather data for the nearest corresponding cities. 

The following information was retrieved from the API call: 
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current Weather description 

## Vacation Search
Based on traveler’s weather preferences, travelers can identify potential travel destinations and nearby hotels. The map showcases destinations using pop-up markers on a marker layer-map.

## Statistical Analysis
The data from global city was plotted. Linear regression was applied to find the relationship between the following variables: 

* Latitude and Maximum Temperature
* Latitude and Humidity
* Latitude and Cloudiness
* Latitude and Wind Speed

### Scatter Plots 
The Scatter plots below were made to show how different weather parameters that changes based on the latitude

![City Latitude vs. Max Temperature](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig1.png)
![City Latitude vs. Max Humidity](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig2.png)
![City Latitude vs. Cloudiness](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig3.png)
![ City Latitude vs. Wind Speed](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig4.png)

### Linear Regression on the Northern and Southern Hemispheres
Linear regression were performed for both the Northern and Southern Hemispheres

#### Maximum Temperature
![Linear Regression on the Northern Hemisphere for Maximum Temperature](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig5.png)
![Linear Regression on the Southern Hemisphere for Maximum Temperature](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig6.png)

#### Percent Humidity
![Linear Regression on the Northern Hemisphere for Percent Humidity](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig7.png)
![Linear Regression on the Southern Hemisphere for Percent Humdity](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig8.png)

#### Percent Cloudiness
![Linear Regression on the Northern Hemisphere for Percent Cloudiness](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig9.png)
![Linear Regression on the Southern Hemisphere for Percent Cloudiness](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig10.png)

#### Wind Speed
![ Linear Regression on the Northern Hemisphere for Wind Speed](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig11.png)
![ Linear Regression on the Southern Hemisphere for Wind Speed](https://github.com/YannMusz/World_Weather_Analysis/blob/main/weather_data/Fig12.png)
