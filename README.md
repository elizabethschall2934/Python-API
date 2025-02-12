# Python-API
Part I - WeatherPy
The purpose of this activity was to create a Python script to visualize a representative model of weather across world cities of varying distance from the
equator.

Technology: Jupyter notebook, Matplotlib or Pandas plotting libraries, Python library and OpenWeatherMap API

Tasks performed:

Create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
After each plot add a sentence or too explaining what the code is and analyzing.

Run linear regression on each relationship, separating them into Northern Hemisphere and Southern Hemisphere:

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots explain what the linear regression is modeling such as any relationships you notice and any other analysis you may have.
Include a written description of three observable trends based on the data.

Requirements:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Part II - VacationPy
The purpose of this activity was to analyze weather data to plan future vacations. 

Technology: Jupyter-gmaps and Google Places API

Create a heat map that displays the humidity for every city from the part I of the homework.

Narrow down the DataFrame to find your ideal weather condition. For example:

A max temperature lower than 80 degrees but higher than 70.

Wind speed less than 10 mph.

Zero cloudiness.

Drop any rows that don't contain all three conditions to be sure the weather is ideal.

Use Google Places API to find the first hotel for each city located within 5000 meters of the obtained coordinates.

Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
Include a screenshot of the heatmap created.
