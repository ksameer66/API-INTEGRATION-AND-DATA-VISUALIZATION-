API-INTEGRATION-AND-DATA-VISUALIZATION
COMPANY : CODETECH IT SOLUTIONS

NAME : K MOHAMMAD SAMEER 

INTERN ID :CT04DZ188

DOMAIN : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

🌤️ Weather Dashboard Using OpenWeatherMap API and Python
This Python project demonstrates how to fetch real-time weather forecast data from the OpenWeatherMap API and visualize it in the form of an interactive weather dashboard using Matplotlib and Seaborn libraries. The main objective of this project is to help users understand and analyze the weather forecast for a specific city through easy-to-understand line charts.

🔍 Project Overview
The project begins by importing the necessary Python libraries:

requests for making HTTP requests to the OpenWeatherMap API,
matplotlib.pyplot for plotting graphs,
seaborn for enhanced and aesthetically pleasing visualizations.
The script uses the OpenWeatherMap 5-day/3-hour forecast API, which provides weather data in 3-hour intervals for the next five days. The user must have a valid API key from OpenWeatherMap, which is free to obtain by registering on their website. The city for which the forecast is to be retrieved is defined in a variable, making it easy to switch between locations.

Once the API key and city name are set, the script constructs the appropriate API URL and sends a GET request using the requests.get() function. The response, returned in JSON format, contains a list of weather forecast entries. Each entry includes temperature, humidity, wind speed, weather description, and the corresponding date and time.

The script then processes the JSON response and extracts four main components:

dates: A list of date-time strings,
temperatures: A list of temperatures in Celsius,
humidity: A list of humidity percentages,
wind_speed: A list of wind speeds in meters per second.
These extracted values are stored in Python lists, which are then used for data visualization.

📊 Data Visualization
To create the weather dashboard, the script uses matplotlib.pyplot.figure() to create a figure with three subplots arranged vertically. Each subplot represents a different aspect of the weather forecast:

Temperature Forecast Chart: This line chart plots the temperature values across the given dates and times. It uses red markers and lines to clearly represent the rise and fall of temperature over the forecast period.

Humidity Forecast Chart: The second chart plots humidity levels using blue markers and lines. It helps users understand how the moisture level in the atmosphere will vary throughout the forecasted days.

Wind Speed Forecast Chart: The third and final chart plots wind speed using green lines with triangle markers. This gives an idea of how strong or calm the wind will be over time.

The seaborn.lineplot() function is used to plot each of the charts for better aesthetics, and plt.xticks(rotation=45) is applied to tilt the date labels for better readability. The charts are formatted with appropriate titles, axis labels, and grid lines.

To organize the layout properly, plt.tight_layout() ensures that subplots do not overlap, and plt.suptitle() adds a main heading at the top of the dashboard with the city name. The plt.subplots_adjust() function is used to fine-tune the spacing so that the title and charts are well-aligned.

✅ Conclusion
This weather dashboard provides a clear and intuitive way to visualize upcoming weather conditions using real-time data. By combining data collection from a public API with powerful visualization libraries like Matplotlib and Seaborn, this project showcases how Python can be used effectively for real-world data analysis and presentation. It's a great learning experience for beginners in data science, API integration, and visualization techniques.

#Output image
<img width="1918" height="965" alt="image" src="https://github.com/user-attachments/assets/7a45cff6-61fb-46f5-88dd-b70d83ea9da9" />
