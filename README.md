
#WEATHER FORECAST APP

Name :- Aniket Gupta 
ID :- CT6WTD55709
Domain :- Web Development 
Duration :- July to September 2024

## Description

The Weather App is a simple and intuitive web application that allows users to check the current weather conditions for a specified location. Users can enter the name of a city and receive real-time weather data, including temperature, weather description, humidity, and wind speed. The app also displays an appropriate weather icon based on the current conditions.

## Features

- **Search Functionality**: Enter a location to get real-time weather updates.
- **Weather Details**: Displays temperature, weather description, humidity, and wind speed.
- **Weather Icons**: Shows an image representing the current weather (e.g., cloud, clear, rain).
- **Error Handling**: Displays a user-friendly message when the location is not found.

## Technologies Used

- **HTML5**: Structure of the app.
- **CSS3**: Styling the app.
- **JavaScript (ES6)**: Logic for fetching and displaying weather data.
- **OpenWeatherMap API**: Source of the weather data.
- **FontAwesome**: Icons for the search button and weather details.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/weather-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd weather-app
    ```
3. Open `index.html` in your preferred web browser.

## Usage

1. Open the Weather App in your web browser.
2. Enter the name of the city in the input box.
3. Click the search button (magnifying glass icon).
4. View the current weather details for the entered location.

## Files

- `index.html`: The main HTML file that contains the structure of the app.
- `style.css`: The CSS file for styling the app.
- `script.js`: The JavaScript file containing the logic for fetching and displaying weather data.

## API Key

The app uses the OpenWeatherMap API to fetch weather data. An API key is required to access the data. The provided key in the JavaScript code is for demonstration purposes. If you want to use your own key, replace the `api_key` variable in the `checkWeather` function with your own API key from OpenWeatherMap.

```javascript
const api_key = "YOUR_API_KEY";
```

## Acknowledgements

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data.
- [FontAwesome](https://fontawesome.com/) for the icons used in the app.
- 
---

Feel free to modify the content as per your needs. This README provides a comprehensive overview of your Weather App, including its features, usage, and necessary setup instructions.
