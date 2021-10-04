# An Analysis of World Weather Using APIs

## Overview of Project

### Purpose

This is an anlayis for a top travel technology company, called PlanMyTrip, that specializes in internet related services in the hotel and lodging industry. We collected and presented data for their customers who filter their search based on their preferred travel criteria to find their ideal hotel anywhere in the world. We perform requests on the OpenWeatherMap API to retrieve the JSON weather data from these cities. After collecting the data we perform exploratory analysis with visualization and visualize travel data using Google's Maps and Places API.

## Results

### Retrieving Weather Data

We generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. We output city weather data as well as retrieve the current weather description for each city. Below is the output of the dataframe containing the udpated weather data.

![Weather_Database.png](https://github.com/alexhuynh0530/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database.png)

### Creating a Customer Travel Destinations Map

We use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers. Below is a screenshot of the output of the marker layer map with a pop-up marker for each city. 

![WeatherPy_vacation_map.png](https://github.com/alexhuynh0530/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_vacation_map.png)

### Creating a Travel Itinerary Map

We use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary. Below you'll find the map of the travel itinerary that shows the route betwen the 4 chosen cities. Next, you'll see the marker layer map with a pop-up marker for each city.

![WeatherPy_travel_map.png](https://github.com/alexhuynh0530/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_travel_map.png)

![WeatherPy_travel_map_markers.png](https://github.com/alexhuynh0530/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_travel_map_markers.png)

## Summary

In summary, we learn that gathering data from an API is more practical and efficient than trying to obtain data directly from a website. In this analysis we also learn how to retrieve data from APIs, store that data in a dataframe, plot the data using matplotlib and Google maps, and perform statistical analysis.
