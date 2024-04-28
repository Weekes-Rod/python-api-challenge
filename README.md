# Python-API-Challenge

- - - - - - - - - - - - - -

## Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

## Before You Begin
- Create a new repository for this project called `python-api-challenge`.
- Clone the new repository to your computer.
- Inside your local Git repository, create a directory for this assignment. Use a folder name that corresponds to the Challenges, such as WeatherPy.
- Inside the folder you just created, add the files called `api_keys.py`, `WeatherPy.ipynb`, and `VacationPy.ipynb`.
- Add a `.gitignore` file to prevent the `api_keys.py` file from being shared with the public.

## Part 1: WeatherPy
- **Requirement 1:** Create Plots to Showcase the Relationship Between Weather Variables and Latitude
  - Use the OpenWeatherMap API to retrieve weather data from the cities list.
  - Create scatter plots for Latitude vs. Temperature, Humidity, Cloudiness, and Wind Speed.
- **Requirement 2:** Compute Linear Regression for Each Relationship
  - Compute linear regression for each relationship.
  - Create scatter plots with linear regression lines for Temperature vs. Latitude, Humidity vs. Latitude, Cloudiness vs. Latitude, and Wind Speed vs. Latitude.

## Part 2: VacationPy
- **Requirement:** Create a map that displays a point for every city in the `city_data_df` DataFrame.
  - Narrow down the dataset to find cities with ideal weather conditions.
  - Use the Geoapify API to find the first hotel located within 10,000 metres of each city's coordinates.
  - Add the hotel name and the country as additional information in the hover message for each city in the map.

## Getting Started
1. Clone this repository to your local machine.
2. Install required Python libraries: pandas, matplotlib, scipy, requests, geopandas, geoViews.
3. Obtain API keys from OpenWeatherMap and Geoapify.
4. Update the `api_keys.py` file with your API keys.
5. Run the `WeatherPy.ipynb` and `VacationPy.ipynb` notebooks to execute the analysis.

## References
- [OpenWeatherMap API Documentation](https://openweathermap.org/api)
- [Geoapify API Documentation](https://www.geoapify.com/api)
- [citipy Documentation](https://github.com/wingchen/citipy)

