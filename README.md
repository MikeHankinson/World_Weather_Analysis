# World Weather Analysis

## Purpose
PlanMyTrip is a top travel technology company that specializes in internet related services in the hotel and lodging industry.    

Collect and present data for customers via the search page which can be filtered based upon preferred travel criteria in order to find an ideal hotel anywhere in the world.  

## Project Plan
* Task: Collect and analyze weather data across cities worldwide.
* Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
* Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.



## Data Collection
* Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
* Use the citipy module to list the nearest city to the latitudes and longitudes.
* Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
* Parse the JSON data from the API request.
* Collect the following data from the JSON file and add it to a DataFrame:
  * City, country, and date
  * Latitude and longitude
  * Maximum temperature
  * Humidity
  * Cloudiness
  * Wind speed
* 
* 
## Exploratory Visualization
* Create scatter plots of the weather data for the following comparisons:
  * Latitude versus temperature
  * Latitude versus humidity
  * Latitude versus cloudiness
  * Latitude versus wind speed
* Determine the correlations for the following weather data:
  * Latitude and temperature
  * Latitude and humidity
  * Latitude and cloudiness
  * Latitude and wind speed
* Create a series of heatmaps using the Google Maps and Places API that showcases the following:
  * Latitude and temperature
  * Latitude and humidity
  * Latitude and cloudiness
  * Latitude and wind speed

These files are located in the attached Resources folder. 

## Visualize Travel Data
Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

1. Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
2. Create a heatmap for the new DataFrame.
3. Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
4. Store the name of the first hotel in the DataFrame.
5. Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.

## Methodology
The data was analyzed using Python code within Jupyter Notebook.  The code incorporated both Pandas and matplotlib.pyplot.  

## Deliverables 
1. 

## Discussion
* 
  
## Recommendations 
* 

----------------------------------------------------------------------------------
### Appendix of Figures and Tables
----------------------------------------------------------------------------------
<br>
<br>
![Fig_1](analysis/Fig1.png)
<br>
<br>
**Fig. 1:  **
<br>
<br>
<br>
![Table 1](analysis/PyBer_fare_summary.png)
<br>
<br>
**Fig. 2:  **
<br>
<br>
<br>
