# WeatherApp_Volley_OpenWeatherMap

An Android application that fetches and displays current weather data using the OpenWeatherMap API and the Volley library for network requests. This app is built using Java and provides real-time information about temperature, humidity, wind speed, and weather conditions.

## Features

- **Real-time Weather Data**: Displays current temperature, humidity, wind speed, and weather description.
- **Networking with Volley**: Utilizes the Volley library to handle HTTP requests efficiently.
- **JSON Parsing**: Parses JSON data from OpenWeatherMap API to extract relevant weather details.

## Technologies Used

- **Java**: Core language for app development.
- **Volley**: Networking library to handle API requests and response caching.
- **OpenWeatherMap API**: Provides weather data for any city in the world.

## Prerequisites

1. Register at [OpenWeatherMap](https://openweathermap.org/api) to obtain an API key.
2. Enable internet permissions in your Android project:
   ```xml
   <uses-permission android:name="android.permission.INTERNET" />

## Setup
Add Volley Dependency: Include the Volley library in your build.gradle file:

1)
dependencies {
    implementation 'com.android.volley:volley:1.2.1'
}

2) API Key: Replace YOUR_API_KEY in the code with your OpenWeatherMap API key.
