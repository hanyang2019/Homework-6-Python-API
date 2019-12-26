![weather](https://scx1.b-cdn.net/csz/news/800/2018/1-whytheweathe.jpg)
# *__Project WeatherPy__*
https://hanyang2019.github.io/Weather_API/
## __Background__
"What's the weather like as we approach the equator?" Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator by using a Python library [CityYy](https://github.com/wingchen/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api).
## __Objectives__
Build a series of scatter plots to analyze the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

## __Results__
* City Latitude vs Max Temperature

![City Latitude vs Max Temperature](https://github.com/hanyang2019/Weather_API/blob/master/Images/l_mf.png?raw=true)
* City Latitude vs Humidity

![City Latitude vs Humidity](https://github.com/hanyang2019/Weather_API/blob/master/Images/l_h.png?raw=true)
* City Latitude vs Cloudiness

![City Latitude vs Cloudiness](https://github.com/hanyang2019/Weather_API/blob/master/Images/l_c.png?raw=true)
* City Latitude vs Wind Speed 

![City Latitude vs Wind Speed ](https://github.com/hanyang2019/Weather_API/blob/master/Images/l_w.png?raw=true)
* Linear Regression Analysis

![Linear Regression Analysis](https://github.com/hanyang2019/Weather_API/blob/master/Images/linear%20regression.png?raw=true)
## __Conclusion__
1.	Although city latitude has a significant linear relationship with wind speed (p value=0.035514 < 0.05), the correlation between them is extremely weak (correlation coefficient=-0.089347) in which it indicates that wind speed decreases with the increase of latitude. Due to limited sample size (approximately 600), the relationship is yet to be confirmed by selecting a larger sample size.

2.	City latitude does not have any significant linear relationship with max temperature, humidity nor cloudiness (P values > 0.05). 

3.	Despite of no linear relationship, it indicates, in the plot of latitude vs max temperature, that city max temperature peaks at latitude of 20 and gradually decreases towards the end of each side.
