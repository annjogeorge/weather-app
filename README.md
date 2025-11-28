# Simple Weather App

A beautiful and responsive weather application built with React that provides real-time weather information for any location around the world.

![Weather App](https://img.shields.io/badge/React-19.1.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-1.10.0-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![OpenWeather](https://img.shields.io/badge/OpenWeather-API-orange?style=for-the-badge&logo=openweathermap&logoColor=white)

## Features

-  **Global Coverage** - Search weather for any city worldwide
-  **Real-time Data** - Get current temperature in Celsius
-  **Detailed Information** - View wind speed, humidity, and "feels like" temperature
-  **Beautiful UI** - Clean and modern design with sunset background
-  **Responsive Design** - Works seamlessly on all devices
-  **Simple Interface** - Just type and press Enter to get weather updates

##  Demo

The app displays:
- Current temperature
- Location name
- "Feels like" temperature
- Humidity percentage
- Wind speed in MPH
  
<img width="1470" height="799" alt="Screenshot 2025-11-28 at 7 05 12 PM" src="https://github.com/user-attachments/assets/1adc6862-0856-4435-93ea-b2e2bea7e885" />

##  Technologies Used

- **React 19.1.0** - Frontend framework
- **Axios** - HTTP client for API requests
- **OpenWeather API** - Weather data provider
- **CSS3** - Custom styling with modern design
- **Google Fonts** - Outfit and Poppins font families

## 📋Prerequisites

Before running this project, make sure you have:

- Node.js (v14 or higher)
- npm or yarn package manager
- An internet connection (for API calls)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/annjogeorge/weather-app.git
   cd weather-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to view the app.

## 📖 Usage

1. Enter the name of any city in the search box
2. Press **Enter** to fetch weather data
3. View the current weather conditions including:
   - Temperature
   - Feels like temperature
   - Humidity
   - Wind speed

## API

This project uses the [OpenWeather API](https://openweathermap.org/api) to fetch real-time weather data.

**Note:** The API key included in the code is for demonstration purposes. For production use, please:
- Get your own API key from [OpenWeather](https://openweathermap.org/api)
- Store it in environment variables for security

## Project Structure

```
weather-app-react/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── assets/
│   │   └── sunset.jpg
│   ├── App.js
│   ├── index.css
│   └── index.js
├── package.json
└── README.md
```

## Customization

You can customize the app by:
- Changing the background image in `src/assets/`
- Modifying colors and styles in `src/index.css`
- Adding more weather parameters from the API
- Implementing weather forecasts
- Adding geolocation for automatic location detection

## Available Scripts

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000)

### `npm test`
Launches the test runner in interactive watch mode

### `npm run build`
Builds the app for production to the `build` folder

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



## Author

**Annjo George**

- GitHub: [@annjogeorge](https://github.com/annjogeorge)


