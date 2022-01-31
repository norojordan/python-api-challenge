# python-api-challenge


# Part I - WeatherPy
In this example, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I used a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
A series of scatter plots was created to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

After each plot, a sentence or two explains what the code is analyzing.
The second requirement is to run linear regression on each relationship. This time, I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, take the time to explain what the linear regression is modeling. For example, describe any relationships you notice and any other analysis you may have.

The final notebook included the following:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Perform a weather check on each of the cities using a series of successive API calls.
Include a print log of each city as it's being processed with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.


# Part II - VacationPy
Next, I used my skills in working with weather data to plan future vacations. I used jupyter-gmaps and the Google Places API for this part of the assignment.


To complete this part of the assignment, the following steps were accomplished:


1. Create a heat map that displays the humidity for every city from Part I.

2. Narrow down the DataFrame to find your ideal weather condition which include temperatues between 75 and 85 degrees, humidity less than 50% and cloudiness less than 50%.

3. Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

4. Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

5. Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.



As final considerations:

You must complete your analysis using a Jupyter notebook.
You must use the Matplotlib or Pandas plotting libraries.
For Part I, you must include a written description of three observable trends based on the data.
For Part II, you must include a screenshot of the heatmap you create and include it in your submission.
You must use proper labeling of your plots, including aspects like: Plot Titles (with date of analysis) and Axes Labels.
For max intensity in the heat map, try setting it to the highest humidity found in the data set.
