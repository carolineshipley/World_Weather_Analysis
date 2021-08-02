# World_Weather_Analysis

## Purpose
The purpose of this project is to create a vacation map that allows the user to apply weather criteria, such as temperature, to identify potential travel destinations. 

Using Google API's allows the user to see a map with recommended hotels based on their destination preferences.

## Overview
To create the vacation map, a list of 2000 random latitudes and longitudes was created. With the coordinates, a list of nearest cities was created using the citipy module. Then, with OpenWeatherMap API was requested the current weather data from each unique city on the list. The map generated provides the users descriptions of the destinations found on the list, including: hotel name, city, country, and current weather and description.
