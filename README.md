# Weather Data Retrieval Projects

## Open-Meteo (No API Key) & OpenWeatherMap (API Key)

This repository contains two Python-based projects demonstrating how to retrieve and process real-time weather data using web APIs. The purpose of this work is to develop a practical understanding of how APIs operate, how to manage authenticated and non-authenticated requests, and how to transform raw web data into structured, analyzable outputs.

Both projects utilize Jupyter Notebook and follow clean, organized code practices that align with professional data analysis workflows.

## 📘 Project Overview
1. Open-Meteo Project (No API Key Required)

This project interacts with the Open-Meteo API, a free and open weather service that does not require authentication.
The notebook demonstrates how to:

- Send parameterized GET requests
- Retrieve current weather conditions and 7-day forecasts
- Interpret weather codes into human-readable descriptions
- Structure and display API responses in a clean format
- Export weather information to a CSV file (weather_data.csv)

Technologies used:
requests, pandas, datetime

2. OpenWeatherMap Project (Requires API Key)

This project communicates with the OpenWeatherMap API, which requires an API key.
It showcases how to:

- Securely load API credentials via .env or Colab Secrets
- Handle API authentication and status codes
- Extract detailed weather information (temperature, humidity, wind, clouds, pressure)
- Convert timestamps for sunrise and sunset
- Organize the data into a structured DataFrame
- Save the output to weather_data_openweathermap.csv
- Generate basic summary statistics

Technologies used:
requests, pandas, dotenv, datetime

## 🎯 Purpose of These Projects

These two implementations were developed to:

- Understand the fundamentals of working with APIs
- Learn how to perform both authenticated and unauthenticated API requests
- Practice data extraction, error handling, and response validation
- Convert raw JSON responses into clean analytical datasets
- Strengthen practical skills in Python programming, web data retrieval, and data organization

They serve as introductory but functional examples of integrating external data sources into Python workflows.
