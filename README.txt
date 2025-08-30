========================================
Weather App - README
========================================

Description:
------------
This is a simple weather web application that allows users to search for a city 
and view its current weather conditions. The app fetches real-time weather data 
from the OpenWeatherMap API and displays details such as:

- Temperature (°C)
- City name
- Humidity (%)
- Wind speed (km/h)
- Weather icon (clouds, rain, clear, etc.)

Files:
------
1. index.html        - Main HTML file (contains structure and JavaScript logic)
2. styles.css        - CSS file for styling the app
3. (Optional) icons  - Weather condition icons are loaded directly from external URLs.

Setup Instructions:
-------------------
1. Download all project files and place them in a single directory.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge).
3. Enter a city name in the search box and click the search button to view weather data.

API Key:
--------
- The app uses the OpenWeatherMap API.
- Default API key is already included in the script (`apiKey` variable).
- If you want to use your own key:
  1. Sign up at https://openweathermap.org/ to get a free API key.
  2. Replace the value of `apiKey` in the script section of `index.html`.

Notes:
------
- Requires internet connection to fetch live weather data and load icons.
- If an invalid city name is entered, an error message will appear.
- Styling can be customized in `styles.css`.

========================================
