# World_Weather_Analysis
Click here to view the analysis files: [WeatherPy.ipynb](https://github.com/caseychen3605/World_Weather_Analysis/blob/main/WeatherPy.ipynb) | [VacationPy.ipynb](https://github.com/caseychen3605/World_Weather_Analysis/blob/main/VacationPy.ipynb)

## Purpose
The purpose of this analysis is to create a vacation map that allows users to apply weather criteria to identify potential travel destinations. By utilizing Google API's, we also provide the user with recommended ideal hotels within there preferred travel destinations.

## Overview
In order to create the vacation map, we generated a list of 1,500 random latitudes and longitudes. With the coordinates, we retrieved and compiled a list of the nearest cities using the citipy module. Then, we used the OpenWeatherMap API to request the current weather data from each unique city on the list. The resulting map provides users with descriptions of the destinations found on our list, including: hotel name, city, country, and current weather and description.
