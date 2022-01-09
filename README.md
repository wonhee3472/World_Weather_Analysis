# World_Weather_Analysis
## Project Overview
This project is to collect and present data for customers through the search page which they will filter based on their preferred travel criteria in order to find their ideal hotel anywhere in the world. 

First, I retrieved the cities for more than 2,000 random latitudes and longitudes using jupyter notebook and citypy module. Then, I performed requests on the `OpenWeatherMap API` and `Google Maps API` to retrieve json weather data and json map data. From these cities I acquired, each data was added to a Panda's dataframe. 

The customers can filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, they will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, I created a travel route between the four cities as well as a marker layer map.