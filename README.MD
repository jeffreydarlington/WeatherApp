# Weather App

## Overview
This is a simple Weather App that allows users to fetch current weather data and a 24-hour forecast for a specified city using the OpenWeatherMap API.

## Features
- Fetches current weather conditions including temperature, weather description, and an icon representation.
- Displays a 24-hour forecast in 3-hour intervals.
- User-friendly UI with an input field and search button.
- Responsive design for various screen sizes.

## File Structure
```
WeatherApp/
│── index.html      # Main HTML file
│── CSS/
│   └── style.css   # Styling file
│── JS/
│   └── script.js   # JavaScript logic
```

## Installation and Usage
1. Clone or download the repository.
2. Open `index.html` in a web browser.
3. Enter a city name and click `Search` to retrieve weather data.

## Dependencies
- OpenWeatherMap API (requires an API key)
- A modern web browser

## API Setup
1. Sign up at [OpenWeatherMap](https://openweathermap.org/) to get an API key.
2. Replace `'YOUR API KEY'` in `/JS/script.js` with your actual API key.

## How It Works
- The `getWeather()` function fetches data from OpenWeatherMap for both current weather and hourly forecast.
- `displayWeather(data)` updates the UI with the fetched current weather details.
- `displayHourlyForecast(data.list)` processes and displays the next 24 hours of weather data.
- Error handling is included to manage network issues and invalid city inputs.

## Styling
The UI is styled using `/CSS/style.css`, which includes:
- A modern card layout for the weather display.
- Input field and button styling.
- Responsive styling for mobile-friendly usage.
- Hover effects for better user interaction.

## Screen Shot
Images/Screenshot 2025-03-20 213851.png
## Credits
- Developed by [jeffreydarlington]
- Weather data provided by OpenWeatherMap
- GitHub: [github.com/devression](https://github.com/devression)
- YouTube: [Dev_ression](https://www.youtube.com/@dev_ression)

## License
This project is licensed under the MIT License.

