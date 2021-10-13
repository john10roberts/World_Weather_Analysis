# World_Weather_Analysis

## Overview of Project
Adding the ability for a user to input data for temperature preferences to filter data for a more individualized vacation search. Additionally, we have added the ability for to create a travel itinerary that will create a travel route between the four selected cities. 

### Weather Database
The weather database folder will house our results from two thousand Random latitudes and longitudes that will be used to generate the initial list of cities that will be used in the vacation search. The folder will contain a jupyter notebook and a csv file. 
![(Weather_Database)](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb)
![WeatherPy_Database](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)

### Vacation Search
The vacation search folder will take the results from the weather database csv and allow users to input data for temperature preferences to generate a map of all the destinations that are within the range of temperatures that a user selects. The map will allow a user to click on a marker and get the following details: 
    - Hotel Name
    - City
    - Country
    - Current Weather
    
The folder will contain a jupyter notebook, a csv file and a png
![(Vacation_Search)](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb)
![WeatherPy_Vacation](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation.csv)
![WeatherPy_Map](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary
The vacation itinerary folder will take the results from the vacation search csv and allow users to select four cities to generate a route between the four cities selected. The map will allow a user to click on a marker and get the following details:
    - Hotel Name
    - City
    - Country
    - Current Weather
    - Max Temp
    
The folder will contain a jupyter notebook and two png files
![(Vacation_Itinerary)](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)
![WeatherPy_Travel_Map](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)
![WeatherPy_Travel_Map](https://github.com/john10roberts/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

