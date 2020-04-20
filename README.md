# World_Weather_Analysis

## Project Overview
For the new modifications to the PlanMyTrip app, you are asked to add more data to the database, or cities DataFrame, so that customers know the weather in the cities when they click on a pop-up marker. You’ll also need to add the amount of rainfall or snowfall within the last three hours so that customers can filter the DataFrame using input statements based on the temperature range and whether or not it is raining or snowing. Finally, you’ll need to create a directions layer Google map that shows the directions between multiple cities for travel.

## Resources
Data Sources: WeatherPy_challenge.csv, WeatherPy_vacation.csv, Google Maps API, OpenWeather API
Software: Jupyter Notebooks, Python, Pandas, Numpy, Matplotlib, Citipy, Statistics, Google Maps

## Summary
I gathered a set of 1,500 random latitudes and longitudes. Located the nearest city using the citipy module. And, performed an API call with the OpenWeatherMap to aquire all the data needed for the updates.
With that data a customer can use choose where they want to travel to based on temperature, rainfall, or snow.
Once the customer has found a city, and info box will appear on the cirt the click on to get hotel and temperature information.
Then, I created a travel map for someone who would want to explore AU.

![Pic1](https://github.com/jugvirpabla/World_Weather_Analysis/blob/master/weather_data/WeatherPy_vacation_map.png.png)

![Pic2](https://github.com/jugvirpabla/World_Weather_Analysis/blob/master/weather_data/WeatherPy_travel_map.png)

![Pic3](https://github.com/jugvirpabla/World_Weather_Analysis/blob/master/weather_data/WeatherPy_travel_map_markers.png)
