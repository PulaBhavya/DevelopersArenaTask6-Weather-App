Weather App 

A simple Python CLI (Command-Line Interface) Weather App that fetches real-time weather information for any city using the OpenWeatherMap API.

-----

Features

* Get current weather details for any city.

     Displays:
  
     City name 
  
     Temperature 

     Humidity 
  
    Weather description 

* Handles invalid city input gracefully.

-------

Requirements

* Python 3.x
* requests library
* Install requests if you don’t have it:

           pip install requests

--------

Setup

1 .Get your API Key from OpenWeatherMap
2. Open weather_app.py (or your file) and replace:

            API_KEY = "YOUR_API_KEY"

with your actual API key.

------------

Usage

Run the app from the terminal:

             python Weather App.py

--------

Enter the city name when prompted:

         ===== 🌍 WEATHER APP =====
        Enter city name: London

        ===== 🌦️ WEATHER REPORT =====
        City: London
        Temperature: 15°C
        Humidity: 72%
        Description: Clouds

If the city is not found:

     ❌ City not found. Please check the name and try again.

-----

How it Works

1. Prompts the user to enter a city name.
2.Sends a request to OpenWeatherMap API using requests.
3.Parses JSON data for temperature, humidity, and weather description.
4.Prints a formatted weather report in the terminal.

-----

License

This project is licensed under the MIT License.
