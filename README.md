# World_Weather_Analysis

Using APIs to visualize weather data (OpenWeatherMap API) Also in this Weekly challenge we will use Google Maps and Places APIs

## Deliverable 1: Retrieve Weather Data

Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap.

Retrieve all of the following information from the API call:

-Latitude and longitude
-Maximum temperature
-Percent humidity
-Percent cloudiness
-Wind speed
-Weather description (for example, clouds, fog, light rain, clear sky)

Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder 


## Deliverable 2: Create a Customer Travel Destinations Map

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

![](/weather_data/ScreenShot_map.png)

## Deliverable 3: Create a Travel Itinerary Map

Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

Selected 4 hotels from 4 markers in Europe

-The directions layer map:

![](/Vacation_Itinerary/WeatherPy_travel_map.png)

-Themarker layer map with a pop-up marker for the cities on the itinerary is created, each marker has the following information:
Hotel name
City
Country
Current weather description with the maximum temperature

![](/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
