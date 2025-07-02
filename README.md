# Weather App 🌤️

A simple **Weather App** that shows the current temperature, location, local time, and weather condition for any searched city using **WeatherAPI**.

![Weather App Screenshot1]([https://via.placeholder.com/800x400.png?text=Weather+App+Screenshot](https://raw.githubusercontent.com/tapasilikithareddy/Weather-app-using-HTML-CSS-JavaScript/refs/heads/main/Weather_screenshot2.jpeg))
![Weather App Screenshot1]([https://via.placeholder.com/800x400.png?text=Weather+App+Screenshot](https://raw.githubusercontent.com/tapasilikithareddy/Weather-app-using-HTML-CSS-JavaScript/refs/heads/main/Weather_screenshot1.jpeg))

---

## 🚀 Features

✅ Shows current temperature in °C  
✅ Displays city name and local time with day of the week  
✅ Shows current weather condition (e.g., Mist, Clear, Rain)  
✅ Allows searching for any city dynamically  
✅ Clean, minimal design using HTML, CSS, and JavaScript

---

## 🌐 Live Demo

[**Click here to view the live Weather App**](https://yourusername.github.io/weather-app/)

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
- [WeatherAPI](https://www.weatherapi.com/) for fetching real-time weather data
- Hosted using **GitHub Pages**

---

## 🗝️ API Key

The app uses a free API key from [WeatherAPI](https://www.weatherapi.com/).  
For your own version:
1. Sign up at [WeatherAPI](https://www.weatherapi.com/) and get your free API key.
2. Replace the existing API key in `script.js`:
   ```js
   let url = `http://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${targetLocation}&aqi=no`;
