# python-api-challenge

### This project explores the use of API's in Python.  In particular, it generates a list of 500+ random latitudes and longitiues, then uses the citypy API to find the nearest city.  They city is then passed to the OpenWeather API to obtain current weather conditions (ie. temp, humidty, wind, etc.). Some further analysis is then done using the weather data and several visualisations are created.

### This repo contains the following files:

#### output_data\cites.csv:  Output of the list of cities along with the weather data.

#### Results_Summary.txt:  Descriptive summary of the results of the analysis.

#### WeatherPy.ipynb:  Jupyter Notebook that contains the Python code to call the API's, perform analysis, and create visualisations.

#### clouds_plot.png:  Plot of cloud cover vs. latitude (output from WeatherPy.ipynb).

#### humidity_plot.png:  Plot of humidty vs. latitude (output from WeatherPy.ipynb).

#### temperature_plot.png:  Plot of temperature vs. latitude (output from WeatherPy.ipynb).

#### wind_plot.png:  Plot of wind speed vs. latutude (output from WeatherPy.ipynb)
