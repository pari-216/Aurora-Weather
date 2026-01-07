# Aurora-Weather
Aurora Weather is a single‑page web app that shows the current weather and a 7‑day forecast with a cinematic, animated UI built using HTML, CSS, and JavaScript. It uses the free Open‑Meteo Weather API, which does not require an API key. 


## Features

- Current weather: temperature, condition, feels‑like, humidity, wind, dew point.
- 7‑day forecast: daily max/min, rain probability, wind, and animated mini icons.
- Beautiful glassmorphism design with glowing gradients and subtle 3D hover.
- Animated weather icons for sun, clouds, rain, snow, and storms (current + forecast). 
- Interactive hover effects on each day card (extra sun burst, faster rain, drifting clouds). 
- Geolocation support to detect the user’s current position, with a fallback to Delhi, India.
- City search with name → coordinates via Open‑Meteo geocoding API. 
- Auto‑refresh of weather data every 15 minutes.

## Tech Stack

- **Frontend**: HTML5, modern CSS3 (flexbox, grid, keyframes, glassmorphism), vanilla JavaScript (no frameworks).
- **Weather API**: [Open‑Meteo Forecast API](https://open-meteo.com/en/docs) for current and daily data. 
- **Geocoding**: Open‑Meteo Geocoding API for converting city names to coordinates. 

## Getting Started

1. Clone or download the project.

2. Place the main file:
   - Save the provided app code as `index.html` in your project folder.

3. Open in a browser:
   - Double‑click `index.html`, or
   - Serve it with a simple static server, for example:

   ```bash
   npx serve .
