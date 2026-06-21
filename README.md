# Climora 🌦
Climora is a modern weather web application that provides real-time weather updates, 5-day forecasts, air quality data, geolocation-based weather, dynamic weather backgrounds, theme switching, and search history.

## Features

### 🌍 Current Weather
- Search weather by city name
- Displays:
  - Temperature
  - Humidity
  - Wind speed
  - Feels like temperature
  - Weather condition
  - Weather icon

---

### 📅 5-Day Forecast
- Shows weather forecast for the next 5 days
- Filters forecast data from 3-hour intervals into daily summaries

---

### 📍 Geolocation Weather
- Fetches weather using the user’s current location
- Uses browser geolocation API

---

### 🌫️ Air Quality Index (AQI)
Displays:
- AQI index
- PM2.5
- PM10
- CO levels

AQI levels:
- 1 = Good
- 2 = Fair
- 3 = Moderate
- 4 = Poor
- 5 = Very Poor

---

### 🎨 Dynamic Weather Backgrounds
Background changes automatically based on weather condition:
- Clear
- Rain
- Clouds
- Snow
- Thunderstorm
- Mist

---

### 🌙 Dark / Light Mode
- Toggle between dark and light themes
- Theme preference saved using localStorage

---

### 🕘 Search History
- Saves last 5 searched cities
- Removes duplicates
- Clickable recent searches
- Stored using localStorage

---

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- OpenWeather API

---

## Project Structure

```plaintext
Climora-weather-app/
│── index.html
│── style.css
│── script.js
│── config.js
│── assets/
│   └── backgrounds/
│── components/
│   ├── weather.js
│   ├── forecast.js
│   ├── geolocation.js
│   ├── aqi.js
│   ├── background.js
│   ├── theme.js
│   ├── history.js
**Smart Weather Intelligence**


## 🛠 Tech Stack

* HTML5
* CSS3
* JavaScript 
* OpenWeatherMap API
* Git & GitHub
* Render (Deployment)


## ⚙ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/goutamii/climora-weather-app.git
```

2. Open the project folder:

```bash
cd climora-weather-app
```

3. Add your OpenWeatherMap API key in `config.js`:

```javascript
const API_KEY = "YOUR_API_KEY";
```
4. Run the project by opening `index.html` in your browser.

## 🌍 API Used

OpenWeatherMap API is used to fetch:

* Current weather data
* Temperature
* Humidity
* Wind speed
* Weather conditions

## 📸 Screenshots

<img width="941" height="499" alt="image" src="https://github.com/user-attachments/assets/7a6e2880-b32d-4400-91cd-114c95b2424a" />


## 🔗 Live Demo

Render Deployment: https://climora-weather-app-127u.onrender.com



## 👩‍💻 Developer

**Goutami Neeli**
