# Weather App

This Weather App is a web application that provides weather information based on the user's location or a searched city name. The app uses the OpenWeatherMap API to fetch current weather data and displays it in a user-friendly interface.

## Features

- Fetches weather data based on user's current location.
- Allows users to search for weather information by city name.
- Displays weather details including temperature, weather description, wind speed, humidity, and cloudiness.
- Shows country flag and weather icons.
- Loading screen during data fetch operations.
- 
# How It Works
Tab Switching:

The app has two tabs: "Your Weather" and "Search Weather".
Clicking on a tab switches the view to the respective section.
User Weather:

When the app loads, it checks for saved coordinates in session storage.
If coordinates are found, it fetches the weather data for those coordinates.
If no coordinates are found, it prompts the user to grant location access.
If location access is granted, it fetches the user's current location coordinates and then the weather data.
Search Weather:

Users can search for weather information by entering a city name in the search form.
The app fetches and displays weather data for the searched city.
Fetching Weather Data:

The app uses the OpenWeatherMap API to fetch weather data.
It handles both successful data fetch and potential errors gracefully.
