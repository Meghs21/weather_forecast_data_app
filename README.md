# 🌤 Weather Forecast App

This Weather Forecast App is a simple application built with Python and Streamlit that provides weather forecasts for the next few days using the OpenWeatherMap API. You can view temperature trends or sky conditions (e.g., clear, cloudy, rainy, snowy) for any location.

## 📋 Features

- **Real-time weather forecasts**: Get the forecast for up to 5 days for any city.
- **Weather Data**: Choose between temperature trends or sky conditions (e.g., clear, cloudy, rainy).
- **Interactive UI**: Easily interact with the app using sliders and drop-down menus.
- **Visualization**: Temperature data is displayed using interactive line charts powered by Plotly, and sky conditions are shown with custom icons.

## 🖼️ Screenshots

![Weather App Screenshot](path/to/screenshot.png)

## 🛠️ Technologies Used

- **Streamlit**: For building the web interface.
- **Plotly**: For data visualization.
- **OpenWeatherMap API**: To fetch weather data.
- **Python**: The core programming language for the app logic.

## 🌐 How It Works

- **Weather Data**: The app fetches data from the OpenWeatherMap API, including temperature and sky conditions for the next few days based on the city you input.
- **Temperature Plot**: If you choose the "Temperature" option, a line graph will show the forecasted temperatures over the next few days.
- **Sky Conditions**: If you choose the "Sky" option, you'll see weather icons for each day (e.g., clear, cloudy, rainy).

## 🔧 API Configuration

To use this app, you need an API key from [OpenWeatherMap](https://openweathermap.org/). Follow these steps to set it up:

1. Sign up for an OpenWeatherMap account and get your API key.
2. Replace the `API_key` variable in `backend.py` with your API key:
    ```python
    API_key = "your_api_key_here"
    ```

## 📧 Contact

If you have any questions, feel free to reach out to me at `meghnamandawra@gmail.com` 

---


