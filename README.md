# Angular-Weather-forecaster
roject Title:
Angular Weather Dashboard

Overview:
This is a single-page application built using AngularJS that allows users to search for real-time weather data of any city. It fetches information from the OpenWeatherMap API and dynamically displays temperature, humidity, wind speed, and optionally a 5-day forecast.

Features:

City-based weather search

Displays:

Temperature (in Celsius)

Humidity (%)

Wind Speed (m/s)

Weather condition icons

Optional 5-day weather forecast

Clean, responsive UI using dynamic templating

AngularJS $http service used for external API integration

Technologies Used:

AngularJS 1.x

HTML5, CSS3

Bootstrap (optional)

OpenWeatherMap API

Installation & Usage:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/angular-weather-dashboard.git
cd angular-weather-dashboard
Open the application:

Simply open index.html in your browser.

Ensure you are running a local server (if required by browser security settings).

API Key Setup:

Sign up at OpenWeatherMap and obtain an API key.

Open app.js (or your main controller file).

Replace "YOUR_API_KEY" with your actual key.

js
Copy
Edit
var apiKey = "YOUR_API_KEY";
File Structure:

pgsql
Copy
Edit
angular-weather-dashboard/
├── index.html
├── app.js
├── styles.css
└── README.txt
