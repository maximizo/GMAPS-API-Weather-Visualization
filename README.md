## Project Description

In this project, I will visualize weather data for 500+ cities with varying distances from the equator. I will then work with this data to set inputs for my ideal vacation weather and determine a location to visit.

### Features & Libraries

* Python
* JSON
* OpenWeatherMap API
* Google Maps API
* Jupyter Notebook:
* Matplotlib
* Pandas
* Numpy
* requests
* time
* scipy
* citipy
* gmaps
* os

## My Process - Part I

1. Create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

2. Run a linear regression on each relationship, separating them into Northern Hemisphere and Southern Hemisphere:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

3. Produce the following in the notebook: 

1. Randomly selected 500 unique cities based on latitude and longitude.
2. A weather check on each of the cities using a series of successive API calls.
3. Include a print log of each city as it's being processed with the city number and city name.
4. Save a CSV of all retrieved data and a PNG image for each scatter plot.

## My Process - Part II

1. Create a heat map that displays the humidity for every city from part I.

2. Narrow down the DataFrame to find my ideal weather conditions: 

  * A max temperature lower than 90 degrees but higher than 75.

  * Wind speed less than 10 mph.

  * Mild cloudiness.

3. Drop any rows that don't contain all three conditions. 

4. Use Google Places API to find the first hotel for each city located within 5000 meters of my coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the hotel name*, city, and country.

## Outputs: 

### Heat Map

  ![heat_map](images/heat_map.png)

### Hotel Map

  ![hotel_map](images/hotel_map.png)

