# 🌎 Python API Challenge: WeatherPy & VacationPy

## 📦 Module 6 Assignment — Data Science & Visualization

---

## 📘 Overview

This project explores the power of APIs, Python, and data visualization by answering the question:  
**“What is the weather like as we approach the equator?”**

By leveraging the **OpenWeatherMap API**, **Geoapify API**, and geographic data, this challenge is broken into two parts:

- **WeatherPy** – Analyze and visualize weather data across 500+ global cities.
- **VacationPy** – Plan ideal vacation locations based on weather and location preferences.

---

## 🔹 Part 1: WeatherPy

### 🧪 Goal:
Create a data-driven representation of weather conditions across the globe using randomly selected cities and determine how weather patterns vary with latitude.

### 🛠️ Tools & Libraries:
- Python
- Jupyter Notebook
- Pandas, Matplotlib, SciPy
- `citipy` (to find nearest city to random coordinates)
- OpenWeatherMap API (for weather data)

### 📊 Key Features:
- Generate 500+ random cities across global coordinates
- Call OpenWeatherMap API to fetch real-time weather data
- Create scatter plots showing relationships between:
  - **Latitude vs. Temperature**
  - **Latitude vs. Humidity**
  - **Latitude vs. Cloudiness**
  - **Latitude vs. Wind Speed**
- Perform linear regression for each plot, divided by:
  - **Northern Hemisphere (latitude ≥ 0)**
  - **Southern Hemisphere (latitude < 0)**
- Overlay regression lines with formulas and r-values

---

## 🔹 Part 2: VacationPy

### 🎯 Goal:
Use the weather data to help plan vacations to cities with ideal weather conditions and visualize these on an interactive map.

### 🛠️ Tools & Libraries:
- Geoapify API (location and place data)
- `geoviews` & `hvplot` (interactive maps and plotting)
- CSV from WeatherPy (weather and coordinates)

### 📍 Key Features:
- Filter cities by ideal weather conditions (e.g., low humidity, warm temp)
- Use Geoapify to find nearby hotels
- Create an interactive map displaying:
  - Hotel locations
  - City name, country, temperature
  - Hover tooltips for easy inspection

---
