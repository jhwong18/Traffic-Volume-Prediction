# Traffic Volume Prediction and Visualization

# Data
This dataset provides hourly traffic volume for a city, including features indicating holidays and weather conditions.
The files used here span from 1st January 2013 to 31st December 2013. The data is acquired from the Minnesota Department of Transportation (www.dot.state.mn.us). The features are shown below:

Attributes:
- `holiday`: US national and regional holidays
- `temp`: average temperature in Kelvin (K)
- `rain_1h`: rain that occured in the hour (mm)
- `snow_1h`: snow that occured in the hour (mm)
- `clouds_all`: percentage of cloud cover
- `weather main`: textual description of current weather
- `weather_description`: longer textual description of current weather
- `date_time`: hour of the data collected in local time

Attribute (Output):
- `traffic_volume`: hourly I-94 reported westbound traffic volume



# Objective
We would first like to understand the understand the trend of the traffic volume across the different months in 2013 and across the different time of the day/week. We would like to what causes an increase and decrease in traffice volume: is it due to certain weather/temperature patterns or due to holiday seasons? By understanding the historical trends of traffic volume and the relationship of the traffic volume with weather/temperature/holidays, we can better identify the features used to predict the weather pattern.

Some questions we would like to investigate:
- What is the traffic volume pattern like, across the different months in 2013?
- What is the traffic volume pattern like, across the different time of the day/week?
- How is the traffic volume related to the weather?
- How is the traffic volume related to the temperature?
- How is the traffic volume related to the holiday seasons?
- Does the combination of bad weather and time of the day/week leads to high traffic volume?
- Does the combination of holiday seasons and time of the day/week leads to high traffic volume?
- Does the combination of bad weather and holiday seasons leads to high traffic volume?

Finally, we would like to predict the traffic volume based on the attributes mentioned above.
