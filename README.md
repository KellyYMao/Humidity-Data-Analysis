# Humidity-Data-Analysis
Using matplotlib, graphs were plotted in python using matplotlib to demonstrate the trends of Relative humidity % (RH%) over time, RH sensor temperature over time, and dewpoint temperature over time using data from a csv file. Other graphs derived from calculations with RH% and RH sensor temperatue were also plotted. 

# Temperature, Relative Humidity, & Dewpoint Relationship Overview
Relative humidity measures the amount of water vapor in the air. Relative Humidity is typically written as a percentage that compares how much water vapor is currently in the air with the amount of water vapor the air could hold if saturated (and at the same temperature). Relative humidity has an inverse relationship with temperature. As temperature increases, the capacity of air to hold water vapor increases. Thus, the relative humidity tends to decrease as temperature increases. Dewpoint Temperature is the temperature at which the air is at 100% RH or saturated with water vapor. 

# Humidity-Data-Analysis
Comparing the trends of these graphs can help us to further understand the relationships between relative humidity, temperature, dewpoint temperature, and the other factors calculated. Understanding these concepts is important as they can be applied as experimental factors to demonstrate the effect of increased presence of water vapor pressure, increased humidity, etc. on materials. Such factors may have an important role to play in the longevity of oxide protective coatings used to prevent metal dusting. 

# RH% 
![RH_change_over_time](/Humidity_Analysis_Graphs/RH_percent_change_over_time.png)  
Graph showing the the changes in RH% over time with data obtained from csv file. 

# RH Sensor Temperature 
![RH_Sensor_Temperature(c)_change_over_time](/Humidity_Analysis_Graphs/RH_Sensor_Temperature(c)_change_over_time.png)  
Graph showing the changes in RH% over time with data obtained from csv file. 

# Dewpoint
![Dewpoint_temperature_(c)_change_overtime](/Humidity_Analysis_Graphs/Dewpoint_temperature_(c)_change_overtime.png)  
Graph showing the changes in dewpoint temperature over time. The dewpoint was calculated based on RH% and RH Sensor Temperature data.

# Saturated Water Vapor
![Saturated_Water_Pressure_change_overtime](/Humidity_Analysis_Graphs/Saturated_Water_Pressure_change_overtime.png)  
Graph showing the changes in saturated water vapor pressure over time. Saturated water vapor pressure was calculated with RH% and RH Sensor Temperature data.

# Water Vapor Pressure
![Water_Vapor_Pressure_change_overtime](/Humidity_Analysis_Graphs/Water_Vapor_Pressure_change_overtime.png)  
Graph showing the changes in water vapor pressure over time. Water vapor pressure was calculated in python with saturated water vapor pressure that was previously obtained. 

# Absolute Humidity
![Water_Vapor_Pressure_change_overtime](/Humidity_Analysis_Graphs/Water_Vapor_Pressure_change_overtime.png)  
Graph showing the the changes in absolute humidity over time. Absolute Humidity was calculated in python with the water vapor pressure that was previously obtained.

# Conclusions

