# python-api-challenge
The Module 6 Challenge is broken down into two deliverables, WeatherPy and VacationPy.
* WeatherPy: Visual analysis of the weather for over 500 cities of varying distances from the equator
* VacationPy: Visual analysis using the Geoapify API and the geoViews Python library to create map visualizations

**Challenge 1: WeatherPy**<br>
The OpenWeatherMap API retrieves weather data from the cities list generated in the started code.

**Part 1:** Coorelation<br>
*A series of scatter plots showcasing the relationship between weather variables and latitude to include:*
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

**Part 2:** Coorelation and Linear Regression<br>
*A series of linear regression models to showcase the following relationships:*
* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

**Challenge 2: VacationPy**
The Geoapify API and geoViews Python library are used in tandem with the weather and coordinates data for each city created in Challenge 1.

**Part 1:**
*A map that displays a point for every city in the city_data_df DataFrame*
![image](https://github.com/RachaelCaldwell/python-api-challenge/blob/main/starter_code/output_data/map_plot_1.png?raw=true)

**Part 2:**
*A filtered DataFrame to showcase ideal weather conditions*

**Part 3:**
*A new DataFrame that uses the Geoapify API to find the first hotel located within 10,000 metres of the given coordinates*

**Part 4:**
*A map that displays the hotel name and the country as additional information in the hover message for each city*
