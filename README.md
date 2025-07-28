# 🌦️ Simple Weather API Server – Vanilla Node.js

A lightweight weather API server built entirely with **vanilla Node.js** — no frameworks like Express. It fetches real-time weather data from **OpenWeatherMap** and responds in clean JSON format.

## 🚀 Features

- ✅ Built using **core Node.js modules**: `http`, `url`, and `https`
- 🔎 Handles GET requests to `/weather?city=CityName`
- 🌍 Fetches real-time weather data from **OpenWeatherMap API**
- 🧠 Gracefully handles errors like:
  - Missing city name
  - Invalid city name
  - Wrong URL path
- ⚡ Handles multiple requests at the same time

## 📦 API Response Includes

- **City Name**
- **Temperature** (in °C)
- **Humidity** (in %)
- **Wind Speed** (in m/s)
