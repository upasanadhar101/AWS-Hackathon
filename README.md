# AWS-Hackathon
# Motivation of study- 
1. The covid times had seen lockdown implemented in many regions. The motivation of the study was to see how the air quality is impacted post covid times with several countries imposing strict lockdown policies.
2. Can this be a future strategy to implement cleaner climate ??

# Method used:  
Data visualization for temporal change in air quality indices and individual pollutants like carbon monoxide, ozone, particulate matter, sulphur dioxide, nitrogen oxides have been plotted on world map. Along with it, data analysis of temporal variation in cumultaive average pollutant concentration through years of 2015 to 2020, has been presented. 

We calculated the cumulative average concentartion of pollutants for each individual cities in different countries and observed how they changed through 2015 to 2020. Since AQI (air quality index) is not available for all cities and countries, we use the cumulative average pollutant concentration in our final data analysis.
We assume atmospheric conditions are constant among each countries throughout the years and work with only maximum pollutants generated at each city during each day of the year. 
First we grouoed the dataset based on cities and found the mean concntration of pollutants for each cities in respective countries. The we used the rating to check the number of cities with low, moderate and high average pollutant concentrations and whether the number of cities falling in these crtieria increases or decreases through the years. 
We treat our inferences based on the values observed in 2020 as post-coovid data and values from year 2015-2019 as pre-covid data.

# Result and Discussion:

The number of cities falling within higher to moderate pollutant concentration range decreases in the year 2020 (post-covid time) with respect to the previous years (pre-covid time). Only 4 cities shows unhealthy conditions with higher average pollutant concnetration in post covid time during the year 2020 while 19 cities showed higher average pollutant concentration duirng the year 2019. The number of cities showing higher average pollutant concentration has decreeased from year 2015 to 2020. 

We also observe that the maximum average pollutant concentration throughout the world observed in 2020 ( post covid time) has decreased significantly with respect to 2019 with decrease% of about 52%. The cities of respective countries with higher average pollutant concentration in 2020 are Israel and India. 

However, the count of number of cities with low average pollutant concentartion (<=51) is less in 2020 with respect to 2019. The cities of respective countries with lower average pollutant concentration in 2020 are Argentina, Algeria,Taiwan, North Macedonia and Israel.

We saw that the count of number of cities showing good/healthy conditions with lower average pollutant concnetration is less post covid time with about 338 cities in 2020 with respect to pre covid time at 2019 when the count of cities with lower pollutant concentration was 355. This may be due to other factors like atmospheric conditions,humidity, temperature etc also contributing to the poolutant concentartion dust/ partculate matter formation in an area.

# Conclusion
From the lower number of cities showing higher pollutant concentration in post covid time in the year 2020, we infer that the average pollutant concentration lowered during post-covid time over certain cities due to lockdwon and consecutively less traffic. However, since other factors like atmospheric conditions, dust formation etc. in an area also contributes to pollutant concentration, the count of number of cities showing good/healthy conditions with lower average pollutant concnetration is less at 2020 in post covid time with respect to pre covid time at 2019 when the count was higher. Also, certain cities like Delhi in India shows approximately the same pollutant concentration throughput and there is not much change in post covid times. 
The lockdown does help in lowering traffic in certain regions and corresponding lowering of regional pollutant concentrations. 

Limitation of this study:- The number of data points collected for each cities vary through years and the cumulative average is based on the data avaialable. This results in some biasness when we are comparing the average concentrations among cities. 
