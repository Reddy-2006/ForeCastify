# ForeCastify
Forecastify is a live weather and air quality web application that allows users to search for any city and view real-time weather conditions, air quality data, and upcoming weather forecasts.

The application retrieves live data from the OpenWeather API and displays important weather information in a clean and responsive interface.

🚀 Features

🔍 City SearchUsers can search for weather information by entering a city name.

🌡️ Current TemperatureDisplays the current temperature of the searched city in Celsius.

☁️ Weather DescriptionShows the current sky condition such as clear sky, cloudy, rain, etc.

📅 Date and Time DisplayDisplays the current date and time based on the weather data received.

🌅 Sunrise & Sunset InformationShows sunrise and sunset timings for the selected city.

🌫️ Air Quality Index (AQI)Displays important air quality metrics such as:

CO (Carbon Monoxide)

SO₂ (Sulfur Dioxide)

O₃ (Ozone)

NO₂ (Nitrogen Dioxide)

📆 5-Day Weather ForecastProvides weather predictions for the next five days using forecast data.

🛠️ Technologies Used

HTML5 – Structure of the web application

CSS3 – Styling and layout

Bootstrap 5 – Responsive design and UI components

JavaScript (ES6) – Application logic and dynamic updates

jQuery – DOM manipulation

OpenWeather API – Fetching real-time weather and air quality data

🌐 API Used

This project uses the weather data services provided by.

APIs used in this project include:

Current Weather API

Air Pollution API

5-Day / 3-Hour Forecast API

These APIs provide real-time weather conditions, air quality data, and weather forecasts.

📂 Project Structure

Forecastify
│
├── index.html
├── index.css
├── README.md
├── search.png
├── cloud.png
├── cloudy.png
├── calendar.png
├── time.png
└── other weather icons

⚙️ How the Application Works

The user enters a city name in the search bar.

The application sends a request to the OpenWeather API.

The API returns weather and air quality data.

JavaScript dynamically updates the webpage with:

City temperature

Weather description

Date and time

Sunrise and sunset timings

AQI metrics

5-day weather forecast

📌 Future Improvements

Possible improvements for future versions of Forecastify:

Dynamic hourly forecast for Today's weather

Weather icons based on real-time conditions

Better UI animations and design improvements

Automatic location detection using GPS

