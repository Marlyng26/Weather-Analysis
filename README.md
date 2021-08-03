In this example, I wrote a Python script to visualize the weather of 500+ cities around the world, each of which is located at a different distance from the equator. I created a representative model of weather across globe cities using a [basic Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api).
The initial requirement was to develop a series of scatter plots that would highlight the following relationships:

* Humidity ( percent ) vs. Latitude * Cloudiness ( percent ) vs. Latitude * Wind Speed (mph) vs. Latitude * Temperature (F) vs. Latitude

The second criterion is that each relationship be subjected to linear regression. This time, divide the plots into Northern Hemisphere (latitude higher than or equal to 0 degrees) and Southern Hemisphere (latitude less than or equal to 0 degrees):


* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
