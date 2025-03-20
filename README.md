# Online Weather Application

## Description
This is a simple online weather application that fetches real-time weather data using the OpenWeather API. Users can enter a city name to check its current weather conditions, including temperature, humidity, and wind speed.

## Features
- Search for weather by city name
- Display temperature in Celsius
- Show humidity and wind speed
- Display appropriate weather icons based on conditions
- Handle invalid city inputs with error messages

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeather API

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/weather-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```
3. Open `index.html` in a browser.

## API Configuration
- The application uses OpenWeather API.
- Ensure you have a valid API key from [OpenWeather](https://openweathermap.org/api).
- Replace the `apiKey` variable in `script.js` with your API key:
  ```js
  const apiKey = "YOUR_API_KEY_HERE";
  ```

## File Structure
```
weather-app/
│-- index.html      # Main HTML file
│-- style.css       # CSS styles
│-- script.js       # JavaScript logic
│-- images/         # Weather icons
```

## How to Use
1. Enter the city name in the search box.
2. Click the search button.
3. View the weather details, including temperature, humidity, and wind speed.
4. If an invalid city is entered, an error message is displayed.

## Author
Developed by [Kuldip Mahale].

## License
This project is licensed under the MIT License.

