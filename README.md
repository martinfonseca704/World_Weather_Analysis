# World_Weather_Analysis


## Project Overview
The opportunity was presented to work in conjunction with PlanMyTrip app. A app that uses weather. They are in the process of a new product, they’ve recommended a few changes to take the app to a level of satisfation. Specifically, they recommended adding the weather description to the weather data that has been retrieved in this project. Subsequently, the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route was created between the four cities as well as a marker layer map.


## Analysis
   First phase was the retrival of weather data. Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data: Latitude and longitude, Maximum temperature, Percent humidity, Percent cloudiness, Wind speed, Weather description.
    Second phase the creation of customer travel destinations map
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers: Hotel name, City, Country, Current weather description with the maximum temperature. "1"
    Final phase consisted of a travel itinerary map
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary. "2"

"1" Vacation_Search/WeatherPy_vacation_map.png
"2" Vacation_Itinerary/WeatherPy_travel_map.png
"2" Vacation_Itinerary/WeatherPy_travel_map_markers.png


## Summary
   This project has made good strides with PlanMyTrip by finding 2,000 cities around the world. The cities had weather information added to them. With all cities, they are tapered down to cities that have preffered temperatures. From there customer picks 4 cities to travel, and the code makes a map that allows them to know how to reach each destination.
