# Climate Resilience Dashboard

## Overview

The Climate Resilience Dashboard is a web-based application designed to monitor environmental data and provide recommendations to enhance climate resilience. Using real-time weather data, air quality indicators, and interactive features, this tool offers tailored suggestions for health and agricultural practices to help users adapt to changing environmental conditions.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Overloaded Subprograms for Recommendations](#overloaded-subprograms-for-recommendations)
- [License](#license)

---

## Features

### 1. Real-Time Weather and Environmental Data
- Displays up-to-date weather conditions based on the user’s city input or geolocation.
- Provides details like temperature, humidity, pressure, and visibility to help users understand current conditions.

### 2. Five-Day Weather Forecast
- Visualized with a line chart using Chart.js to show max and min temperatures over the next five days.

### 3. Air Quality Monitoring
- Real-time Air Quality Index (AQI) with color-coded levels (Good, Fair, Moderate, Poor, Very Poor) to quickly convey pollution levels and their health implications.

### 4. Interactive Location Map
- Integrated with Leaflet to display a map centered on the user’s location, visually contextualizing the environmental data.

### 5. Health and Crop Recommendations for Climate Resilience
- Generates context-specific health and agricultural recommendations based on real-time weather data, supporting users in adapting their activities to current and forecasted conditions.

---

## Technologies Used

- **React**: For creating a responsive and interactive user interface.
- **Axios**: For fetching data from the OpenWeatherMap API.
- **Leaflet**: For rendering the interactive map that provides location-based data visualization.
- **Chart.js**: For displaying the five-day temperature forecast in a line chart.
- **OpenWeatherMap API**: To retrieve real-time weather, air quality, and forecast data.

---

## Getting Started

### Prerequisites
- Node.js and npm installed on your machine.
- An API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) for accessing weather data.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Climate-Resilience-Dashboard.git
    cd Climate-Resilience-Dashboard
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up the environment:
    - Create a `.env` file in the project root and add your OpenWeatherMap API key:
      ```plaintext
      REACT_APP_WEATHER_API_KEY=your_openweathermap_api_key
      ```

4. Start the development server:
    ```bash
    npm start
    ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the dashboard.

---

## Usage

- **Search for Weather Data**: Enter a city name to retrieve real-time weather information or use the "Location" button to enable geolocation.
- **View Forecast**: See a five-day temperature forecast to prepare for upcoming weather patterns.
- **Monitor Air Quality**: Check the air quality index and corresponding health recommendations.
- **Access Recommendations**: Get tailored advice for both health and agricultural practices based on current conditions.

---

## Overloaded Subprograms for Recommendations

The `generateRecommendations` function in this project simulates overloading by tailoring its output based on specific weather conditions, providing distinct recommendations for different scenarios:

- **Rainy Weather**: Health tip to carry an umbrella; agricultural suggestion to delay harvesting.
- **Sunny Weather**: Health recommendation to use sunscreen; agricultural advice to irrigate crops.
- **Snowy Conditions**: Suggests wearing warm layers for health and frost-resistant practices for crops.

This approach emulates function overloading by dynamically adjusting the output based on the environmental context, making the tool adaptable and user-specific.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

For more details and to explore the code, visit the GitHub repository: [Climate Resilience Dashboard](https://github.com/yourusername/Climate-Resilience-Dashboard)
