# Python API Homework - What's the Weather Like?

## Summary
### WeatherPy:
* The Python code randomly selects a group of 500+ cities across the world. Then, the code collects data from the OpenWeatherMap API to create a representatitve model of weather across world cities. The API data is used to graph the following relationships:
    * Temperature (F) vs. Latitude
    * Humidity (%) vs. Latitude
    * Cloudiness (%) vs. Latitude
    * Wind Speed (mph) vs. Latitude
### VacationPy:
* Weather data from WeatherPy is used to generate jupyter-gmaps with Google Places API to find ideal conditions for a hypothetical vacation.
    * The following metrics were used to find the ideal weather conditions:
    * A max temperature lower than 80 degrees but higher than 70.
    * Wind speed less than 10 mph.
    * Zero cloudiness.
* Analysis is also used in a mockup website for another project. 
* See the following link: https://jrosedavis.github.io/Web-Design-Challenge/
### Files
* The analysis includes the following files:
    * Folder WeatherPy "main HW6.ipynb" Jupyter Notebook that contains the Python code for the analysis.
    * Folder VacationPy "HW6 VacationPy.ipynb" Jupyter Notebook that contains heatmap displays using the data from Weatherpy.
    * 'Images' folder includes output figures from both sets of analysis.

