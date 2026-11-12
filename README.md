# Weatherly - Modern Forecast

A fully responsive, modern weather dashboard built entirely with HTML5, CSS3, and Vanilla JavaScript (ES6+). It fetches real-time data from the Open-Meteo API and uses custom SVG icons.

## Features
- **Real-time Weather**: Current conditions, hourly, and 7-day forecasts.
- **Location Search**: Autocomplete city search powered by Open-Meteo Geocoding.
- **Geolocation**: "Use My Location" button utilizing the native Browser Geolocation API.
- **Theming**: Dark and Light modes saved in `localStorage`.
- **Units**: Celsius/Fahrenheit and km/h / mph toggles.
- **Native SVG Graphics**: Zero emojis, zero image files. All custom inline scalable vector graphics.
- **Mobile Responsive**: Completely fluid layout adjusting to Desktop, Tablet, and Mobile views flawlessly (fixing grid stacking and horizontal overflow).

## How to Run

1. Clone or download this repository.
2. Open the folder in **VS Code**.
3. Install the **Live Server** extension (by Ritwick Dey) if you haven't already.
4. Right-click on `index.html` and select **"Open with Live Server"**.
5. The application will launch in your default web browser at `http://127.0.0.1:5500/index.html`.

## Testing Instructions
- **City Search**: Type "Tokyo" or "New York" in the search bar. Wait 500ms for the debounced dropdown to appear, then click a result.
- **Geolocation**: Click the target icon next to the search button. Your browser will ask for location permission. Click "Allow" to see your local weather.
- **Themes & Units**: Click the Sun/Moon icon or the °C/°F buttons in the top right to watch the interface adapt instantly.

## API Endpoints Used
- **Forecast**: `https://api.open-meteo.com/v1/forecast`
- **Geocoding**: `https://geocoding-api.open-meteo.com/v1/search`
*Weather data provided free by [Open-Meteo](https://open-meteo.com/).*
