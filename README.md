# Module 6 | WeatherPy

## Overview
Traveling is one of the most enjoyable experiences to everyone however weather conditions can influence trip planners travel behavior and impact their overall experience throughout the trip. The purpose of this project is to gather weather data worldwide, analyze and visualize weather data  worldwide across the globe. This project will provide as a tool for travel planners or individuals which will allow them to determine their destination based on their choice of weather conditions.


## Resources to Complete Analysis

>•	Jupyter Notebook: [Weather_Database.ipynb](https://github.com/rpamintuan671/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.ipynb), [Vacation_Search.ipynb](https://github.com/rpamintuan671/World_Weather_Analysis/blob/main/Vacation%20Search/Vacation_Search.ipynb),  [Vacation_Itenary.ipynb](https://github.com/rpamintuan671/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb)

>•	Pythoon Dependencies: SciPy, Python Requests, Pandas, JSON Traversals Matplotlib, CitiPy

>•	CSV Files: [WeatherPy_vacation.csv](https://github.com/rpamintuan671/World_Weather_Analysis/tree/main/Vacation%20Search), [Weather_Databases.csv](https://github.com/rpamintuan671/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.csv)

## Weather Database
A set of 2,000 random latitudes and longtitudes were generated and nearest city were retrieved and performed an API call with the OpenWeatherMap.



### The following information were retrieved from the API call:
>•	Latitude and longitude

>•	Maximum temperature

>•	Percent humidity

>•	Percent cloudiness Wind speed

>•	Weather description(form example, clouds, fog, light rain, clear sky)

## Vacation Search
Vacation planners can search travel destination based on their weather condition preferences and search for nearby hotel. The map below showcases example travel destinations using pop-up markers on a marker layer-map.
![WeatherPy_vacation_map](https://user-images.githubusercontent.com/106283411/182930704-4517d23e-0c20-4947-9082-c4ccb88c30ca.png)

 



## Vacation Itinerary
Google Directions API was used to create a travel itinerary that shows route between four cities chosen by the trip planner. A marker layer map with pop-up marker for each city on the itinerary.

### Travel Map with Markers
![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/106283411/182935916-90918ca8-9c1c-4731-9fb6-137d654dad09.png)




### Travel Map Route by Driving

![WeatherPy_travel_map](https://user-images.githubusercontent.com/106283411/182936279-38b7bcf1-a9f0-4f96-92b9-9363d006b16e.png)


 





