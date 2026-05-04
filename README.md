# 🌤️ Weather App

> Real-time weather at your fingertips — search any city and get live conditions instantly.

![Weather App Interface](screenshots/preview.png)

---

## ✨ Features

- 🔍 **City Search** — Look up weather for any city in the world
- 🌡️ **Live Temperature** — Displays current temperature in °C
- 💧 **Humidity** — Real-time humidity percentage
- 🌬️ **Wind Speed** — Current wind speed in km/h
- 🎨 **Dynamic Weather Icons** — Icons change based on weather condition (Rain, Clear, Clouds, Drizzle, Mist)

---

## 🖥️ Demo

> Search for any city and the app fetches live data from OpenWeatherMap API.

| Clear Sky ☀️ | Rainy 🌧️ | Cloudy ⛅ |
|---|---|---|
| ![clear](screenshots/clear.png) | ![rain](screenshots/rain.png) | ![clouds](screenshots/clouds.png) |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling & Layout |
| Vanilla JavaScript | Logic & API calls |
| [OpenWeatherMap API](https://openweathermap.org/api) | Live weather data |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2. Get your API key

- Sign up at [openweathermap.org](https://openweathermap.org/)
- Go to **API Keys** in your account dashboard
- Copy your key

### 3. Add your API key

Open `index.html` and replace the placeholder:

```js
const apiKey = "YOUR_API_KEY_HERE";
```

### 4. Run the app

Just open `index.html` in your browser — no build step needed!

```bash
open index.html   # macOS
start index.html  # Windows
```

---

## 📁 Project Structure

```
weather-app/
│
├── index.html          # Main app file
├── style.css           # Stylesheet
├── README.md           # You're reading this!
│
└── images/
    ├── search.webp
    ├── humidity.png
    ├── wind.png
    ├── clear.png
    ├── rain.webp
    ├── heavy-rain.png
    ├── drizzle.png
    └── mist.png
```

---

## ⚠️ Important Note

> **Do not expose your API key publicly.** If you fork/publish this project, either use environment variables or restrict your key on the OpenWeatherMap dashboard (by HTTP referrer).

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ using OpenWeatherMap API</p>