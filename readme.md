# JS Weather App

A simple and visually appealing weather app built with HTML, CSS, and JavaScript that fetches real-time weather data using the OpenWeather API.

## Features
- Search for the current weather of any city by entering the city name.
- Displays temperature, city name, humidity, wind speed, and a weather icon.
- Provides error handling for invalid city names.
- Responsive design with modern styling.

## Technologies Used
- **HTML**: For structuring the app.
- **CSS**: For styling and creating an attractive UI.
- **JavaScript**: For fetching and displaying dynamic weather data.
- **OpenWeather API**: For accessing real-time weather information.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd weather-app
   ```

3. **Set Up API Key**
   - Obtain an API key from [OpenWeather](https://openweathermap.org/api).
   - Replace the `apiKey` variable in the `script` tag of `index.html` with your API key:
     ```javascript
     const apiKey = "YOUR_API_KEY_HERE";
     ```

4. **Open the App**
   Open `index.html` in your favorite browser to run the app.

## Usage

1. Enter the name of a city in the search bar.
2. Click the search button.
3. View the weather details displayed, including:
   - Temperature
   - Humidity
   - Wind speed
   - Weather condition (with an icon)

## File Structure

```plaintext
weather-app/
├── index.html  # Main HTML file
├── style.css   # Styling for the app
├── img/        # Images for weather icons
└── README.md   # Project documentation
```

## Screenshots

**Home Screen:**
![Home Screen](screenshot-home.png)

**Search Result:**
![Search Result](screenshot-search.png)

## Live Demo
Check out the live demo [here](https://your-live-demo-url.com).

## License
This project is open source and available under the [MIT License](LICENSE).