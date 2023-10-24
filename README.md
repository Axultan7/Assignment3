# Assignment3
Weather Data Integration
This project demonstrates how to integrate weather data from multiple sources and adapt it to a common format for use in a mobile application. It includes classes to fetch weather information from two different providers: OpenWeatherMap and WeatherAPI.

Table of Contents
Introduction
Project Structure
Usage
Contributing
License
Introduction
This project showcases a simple weather data integration system that consists of several key components:

WeatherData class: Represents weather information, including location, temperature, and condition.

WeatherProvider interface: Defines a contract for classes that can provide weather data for a specific location.

OpenWeatherMapProvider class: Implements the WeatherProvider interface for fetching weather data from OpenWeatherMap. It simulates fetching data by creating a map with sample weather data.

WeatherAPIProvider class: Implements the WeatherProvider interface for fetching weather data from WeatherAPI. Similar to the OpenWeatherMapProvider, it uses a map with sample weather data.

OpenWeatherMapAdapter and WeatherAPIAdapter classes: These classes adapt the data from the providers to the common WeatherData format.

MobileApp class: Demonstrates how to use the adapters to display weather information for different locations.

Project Structure
The project structure is organized as follows:

WeatherData: Represents the common weather data model.

WeatherProvider: Defines the interface for weather data providers.

OpenWeatherMapProvider and WeatherAPIProvider: Implement the WeatherProvider interface for specific data sources.

OpenWeatherMapAdapter and WeatherAPIAdapter: Adapt data from the providers to the common format.

MobileApp: A sample mobile application that uses the adapters to display weather data for specific locations.

Usage
To use this project, follow these steps:

Clone the repository to your local environment.

Open the project in your preferred Java development environment.

Run the MobileApp class to display weather data for specific locations. You can provide different locations as arguments in the displayWeather method.
