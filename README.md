# Real Time Weather Monitoring and Analysis </br>

## Objective : 
To provide a comprehensive, real-time view of current weather conditions, enabling informed decision-making and proactive responses to potential weather-related issues. </br>

## Description of Data :
The dataset used in this project contains weather-related information and consists of the following columns:

Row ID: A unique identifier for each data entry. </br>
Location: The geographical area where the data was recorded. </br>
MinTemp: Minimum temperature (in degrees Celsius) recorded for the day. </br>
MaxTemp: Maximum temperature (in degrees Celsius) recorded for the day. </br>
Rainfall: The amount of rainfall (in mm) recorded for the day. </br>
Evaporation: The amount of evaporation (in mm) recorded for the day. </br>
Sunshine: The total sunshine duration (in hours) for the day. </br>
WindGustDir: The direction of the strongest wind gust recorded for the day. </br>
WindGustSpeed: The speed (in km/h) of the strongest wind gust recorded for the day. </br>
WindDir9am: Wind direction observed at 9:00 AM. </br>
WindDir3pm: Wind direction observed at 3:00 PM. </br>
WindSpeed9am: Wind speed (in km/h) recorded at 9:00 AM. </br>
WindSpeed3pm: Wind speed (in km/h) recorded at 3:00 PM. </br>
Humidity9am: Relative humidity (in percentage) recorded at 9:00 AM. </br>
Humidity3pm: Relative humidity (in percentage) recorded at 3:00 PM. </br>
Pressure9am: Atmospheric pressure (in hPa) recorded at 9:00 AM. </br>
Pressure3pm: Atmospheric pressure (in hPa) recorded at 3:00 PM. </br>
Cloud9am: Fraction of the sky covered by clouds (measured in oktas) at 9:00 AM. </br>
Cloud3pm: Fraction of the sky covered by clouds (measured in oktas) at 3:00 PM. </br>
Temp9am: Temperature (in degrees Celsius) recorded at 9:00 AM. </br>
Temp3pm: Temperature (in degrees Celsius) recorded at 3:00 PM. </br>
RainToday: Indicates whether it rained (Yes/No) on the day. </br>
This dataset enables the analysis of weather patterns, predictions, and trends over time and is crucial for decision-making in applications such as forecasting and monitoring. </br>

## Queries
![image](https://github.com/user-attachments/assets/bffe6eef-0963-4599-ae9d-3a2c044abf97)

1. Rain Today Status : What proportion of locations are currently reporting rain?
2. Humidity and Pressure Relationship :  How do humidity and pressure levels change in relation to each other over time?
3. Extreme Wind Gust Events : Which locations have experienced wind gusts exceeding 40 (units unspecified) in the last hour?
4. Real-Time Humidity and Pressure (Grouped Hourly) : How are humidity and pressure levels changing in real-time, and are there any notable trends or anomalies?
5. Sunshine vs. Evaporation : How does the amount of sunshine affect evaporation rates, and how does wind speed play a role in this relationship?
6. Maximum Temperature in the Last Hour : What was the maximum recorded temperature in the last hour? 
7. Wind Speeds (9AM vs 3PM) by Location : How do wind speeds at 9 AM compare to those at 3 PM in various locations? 
8. Real-Time Temperature Variation :  How much does the temperature vary over short periods within the last hour? 

## Managerial Insights :
    Query 1: Rain Today Status:
    *   Transportation: Knowing the proportion of locations experiencing rain enables logistics managers to optimise routes, anticipate delays, and potentially issue warnings to drivers.
    *   Event Management: For outdoor events, this information is crucial for planning rain contingency measures, such as providing shelter or rescheduling.
    *   Agriculture: Farmers can use this data to make decisions about irrigation, harvesting, and the application of pesticides or fertilisers, which are affected by rainfall.
    
    Query 2: Humidity and Pressure Relationship:
    *   Construction: Understanding pressure and humidity trends can inform decisions regarding the pouring of concrete or the application of certain building materials, which are sensitive to these conditions.
    *   Aviation: Changes in pressure and humidity can impact aircraft performance and flight safety. Monitoring these trends allows for better flight planning and safety precautions.
    
    Query 3: Extreme Wind Gust Events:
    *   Aviation: This query provides critical information for aviation safety, enabling the grounding of flights or rerouting of aircraft to avoid hazardous wind conditions.
    *   Construction and Infrastructure: High wind speeds can pose risks to construction sites and infrastructure. Real-time alerts allow for precautionary measures, such as securing equipment or halting operations.
    *   Public Safety: Alerts can be issued to the public to warn of potential dangers from high winds, such as falling trees or debris.

    Query 4: Real-Time Humidity and Pressure (Grouped Hourly):**
    *   Manufacturing: Many industrial processes are sensitive to humidity and pressure changes. Real-time monitoring enables adjustments to maintain product quality and operational efficiency.
    *   Storage and Warehousing: Humidity control is crucial for preserving the quality of stored goods, especially perishable items. 

    Query 5: Sunshine vs. Evaporation:
    *   Agriculture: Farmers can use this data to optimise irrigation schedules and water usage, considering the combined effects of sunshine and evaporation.
    *   Water Resource Management: Understanding evaporation rates is crucial for managing reservoirs and water supplies, especially in regions with limited water resources.
    
    Query 6: Maximum Temperature in the Last Hour:
    *   Public Health:  Knowing the maximum temperature allows public health officials to issue heat advisories and implement measures to prevent heat-related illnesses.
    *   Energy Consumption: High temperatures can lead to increased demand for cooling, impacting energy grids.  Monitoring peak temperatures helps in forecasting energy needs and managing supply.

    Query 7: Wind Speeds (9AM vs 3PM) by Location:
    *   Renewable Energy: Wind farms can use this data to optimise energy generation based on expected wind patterns at different times of the day.
    *   Outdoor Activities: This information can be used to plan outdoor activities, such as sailing or kite flying, based on favourable wind conditions.
    
    Query 8: Real-Time Temperature Variation:
    *   Agriculture: Understanding temperature fluctuations helps farmers protect crops from frost damage or heat stress.
    *   Urban Planning: Monitoring temperature variations in urban areas can inform strategies to mitigate the urban heat island effect, such as planting trees or using reflective surfaces.

By leveraging these insights, managers across diverse industries can make more informed decisions, enhance operational efficiency, mitigate risks, and improve overall outcomes.



