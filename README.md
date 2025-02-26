# Weather-Dashboard-OpenWeather-API-
This project fetches real-time weather and forecast data for UK cities using the OpenWeather API and visualizes temperature & humidity trends using Python, Matplotlib, and Seaborn. It allows users to compare actual vs. forecasted weather conditions interactively.

# 🌦️ Weather Dashboard using OpenWeather API 📊

## Project Overview
This project retrieves **real-time weather data** and **5-day forecasts** for any UK city using the **OpenWeather API** and visualises **temperature & humidity trends**. The goal is to compare **actual vs. forecasted weather conditions** clearly and interactively.

## Features
**Fetches real-time weather data** from the OpenWeather API  
**Retrieves 5-day forecast** for trend analysis and saves to a .csv file for a weather dashboard generation.
**Plots temperature & humidity trends**
**Compares actual vs. forecast data**  
**User input-based visualization** for dynamic city selection  

## Requirements
To run this project, install the following dependencies:
```bash
pip install requests pandas matplotlib seaborn

API key: dd8cedb72349b0f32a7715bb048eea3b

https://api.openweathermap.org/data/2.5/weather?lat=44.34&lon=10.99&appid={API key}
https://simplemaps.com/data/gb-cities#:~:text=Below%20is%20a%20list%20of%20258%20prominent%20cities,the%20fields%29%20that%20you%27ll%20find%20in%20our%20.

>- requests: For API calls
>- pandas: For data storage & manipulation
>- streamlit: (Optional) To build a simple UI
>- geopy: To get coordinates for UK cities
