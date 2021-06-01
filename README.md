# World_Weather_Analysis

## Project Overview

Collect and present city, hotel, and weather data for travel technology app "PlanMyTrip." 

First, a weather database was generated based on 2000 random latitude and longitude combinations by making requests to the OpenWeather API to retrieve a maximum temperature, weather description, % humidity, cloudiness and windspeed.  Weather database is provided in CSV format as file "WeatherPy_Database.csv."  Script and database files are provided in folder Weather_Database.

Second, WeatherPy_Database is filtered based on user input statements for desired weather conditions and a new database is generated with recommended hotel destinations that meet the input specifications. The new database is exported to CSV format in the file "WeatherPy_vacation.csv."  Destinations are visually represented in a travel destination map with pop-up markers identifying hotel and weather information using the Google Maps and Places API.  Script, database, and a screenshot of the map generated are provided in the folder Vacation_Search. 

Finally, a multi-destination travel itinerary is generated from the user's possible travel destinations in the WeatherPy_vacation database.  The travel route is displayed using the Google Directions API along with a marker layer map with pop-up markers indicating hotel, city, and weather information. Script is provided along with example screenshots of the maps generated in the folder Vacation_Itinerary. 

## Resources

The software used to generate the scripts included Python 3.7.10 with Jupyter Notebook 6.3.0 and scripts are provided as *.ipynb files.
