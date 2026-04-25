# 🌦️ WeatherWave

> A fully featured, real-time weather dashboard built with vanilla HTML, CSS & JavaScript.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-API-orange?style=for-the-badge)

---

## 🔗 Live Demo

👉 **[ritu1529.github.io/Weather-Wave](https://ritu1529.github.io/Weather-Wave/)**

---

## ✨ Features

- 🔍 **City Search** — Search weather for any city in the world
- 📍 **My Location** — Auto-detect weather using browser geolocation
- 🌡️ **°C / °F Toggle** — Switch temperature units instantly
- 🕐 **Search History** — Last 6 searched cities saved locally
- 🌅 **Sunrise & Sunset** — Exact times based on city timezone
- 💨 **Weather Stats** — Humidity, wind speed, visibility, pressure
- 🌿 **Air Quality Index** — Color-coded AQI with Good/Moderate/Poor levels
- 📊 **24-Hour Chart** — Hourly temperature graph using Chart.js
- 🗺️ **Live Map** — Interactive city location map (OpenStreetMap)
- 📅 **5-Day Forecast** — Daily high/low with weather icons
- 🔔 **Rain Alerts** — Browser push notifications when rain is detected
- 🌐 **Multi-Language** — English, Hindi, French, Spanish, German, Japanese, Arabic
- 🎨 **Dynamic Themes** — Background changes with weather (sunny, rainy, snowy, etc.)

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | App structure |
| CSS3 | Styling, animations, dynamic themes |
| JavaScript (Vanilla) | Logic, API calls, DOM manipulation |
| OpenWeatherMap API | Weather, forecast & AQI data |
| Chart.js | 24-hour temperature chart |
| OpenStreetMap | Embedded city map |
| LocalStorage | Search history persistence |
| Geolocation API | Device location detection |
| Notifications API | Rain alert push notifications |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Ritu1529/Weather-Wave.git
cd Weather-Wave
```

### 2. Get a free API key
- Sign up at [openweathermap.org](https://openweathermap.org/api)
- Go to **My API Keys** and copy your key
- The free plan allows 1,000,000 calls/month — more than enough!

### 3. Add your API key
Open `WeatherWave.html` and find this line near the top of the `<script>` section:
```javascript
const API_KEY = 'YOUR_API_KEY_HERE';
```
Replace it with your actual key:
```javascript
const API_KEY = 'your_actual_key_here';
```

### 4. Run the app
Just open `WeatherWave.html` in any browser — no build tools, no dependencies!

Or use the **Live Server** extension in VS Code for hot reload.

---

## 📁 Project Structure

```
Weather-Wave/
│
└── WeatherWave.html      # Complete app — HTML + CSS + JS in one file
└── README.md             # Project documentation
```

---

## 📸 Screenshots

> Search your city and get instant results with a beautiful dynamic UI

| Sunny Theme | Rainy Theme | Snowy Theme |
|---|---|---|
| ☀️ Orange gradient | 🌧️ Dark blue tones | ❄️ Light blue/white |

---

## 🌐 APIs Used

- **[OpenWeatherMap Current Weather](https://openweathermap.org/current)** — Live weather data
- **[OpenWeatherMap 5-Day Forecast](https://openweathermap.org/forecast5)** — 5-day / 3-hour forecast
- **[OpenWeatherMap Air Pollution](https://openweathermap.org/api/air-pollution)** — AQI data
- **[OpenStreetMap](https://www.openstreetmap.org/)** — Embedded city map (no key needed)

---

## 💡 What I Learned

- Fetching and handling data from REST APIs using `fetch()`
- Using `Promise.all()` to run multiple API calls simultaneously
- Working with Browser APIs — Geolocation, Notifications, LocalStorage
- Building dynamic UIs that respond to real data
- CSS animations and theme switching based on weather conditions
- Integrating third-party libraries (Chart.js)
- Deploying a static site with GitHub Pages

---

## 🔮 Future Improvements

- [ ] Add UV Index data
- [ ] Weekly forecast (7-day)
- [ ] Weather history graphs
- [ ] PWA support (installable app)
- [ ] Dark/light manual toggle

---

## 👩‍💻 Author

**Ritu**
- GitHub: [@Ritu1529](https://github.com/Ritu1529)
- Project: [Weather-Wave](https://github.com/Ritu1529/Weather-Wave)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this project useful, please give it a star on GitHub!
