## API-Challenge
# **WeatherPy and Vacation Py**
_______________________________
**Background**


_______________________________

Part 1:  What's the Weather Like?  

Look at 500 or more random cities, using the OpenWeatherMap API, analyze possible relationships between Latitude and the following factors:
  * Maximum Temperature
  * Humidity
  * Cloudiness
  * Wind Speed

Part 2:  Where to Travel Next?

Using the data from Part 1, create a Humidity Heat Map of the 500+ cities.  By narrowing down the list to cities with ideal weather conditions, find the nearest hotels and plot those locations on the Humidity Heat Map.

_______________________________
**Observations**


_______________________________

  * As expected, the closer the latitudes are to the equator, the hotter the maximum temperatures.  By comparing the maximum temperatures of the Northern and Southern Hemispheres separately, the r-value calculated confirms this relationship.

* When looking at humidity and cloudiness, the plots do not appear to show a relationship. The linear regression models which examine both the Northern and Southern Hemispheres confirm the weak correlation for both humidity and cloudiness, respectively.  Other factors could explain the small r-values, such as a city's proximity to bodies of water or even altitude.

* The wind speeds are generally below 15mph across all the latitudes acquired for this sample.  When looking at the wind speeds between the Northern and Southern Hemispheres, there might be a correlation, however more analysis is required.


*Please find included: WeatherPy and Vacation Py directories with the resource data file, required images and the Jupyter Notebook files*
