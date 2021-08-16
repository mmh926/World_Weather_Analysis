# World_Weather_Analysis ReadMe

BY: MONICA HOLMES
04/04/2021



# PURPOSE

## Project Overview
At the most fundamental level, Jack needs help answering a question: How might we provide real-time suggestions for our client's ideal hotels? My first task was to define what was meant by "ideal." So, over the course of the conversation with Jack, I narrowed that to hotels that were (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for the client.


Jack loved the PlanMyTrip app created in the module. Beta testers loved it as well and recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data already retrieved in this module. Then, have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, create a travel route between the four cities as well as a marker layer map.




## Basic Project Plan

Here's an outline of my project plan:

 •	Task: Collect and analyze weather data across cities worldwide.
 
 •	Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
 
 •	Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.


## Challenge Deliverables 


## Deliverable 1: Retrieve Weather Data:
Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data I gathered in the module, use my API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.




## Deliverable 2: Create a Customer Travel Destinations Map:
Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.


## Deliverable 3: Create a Travel Itinerary Map:
Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.
