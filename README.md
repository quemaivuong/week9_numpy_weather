# 7-Day Weather Analysis 🌤️

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Description

This Python project allows users to **input any city** and fetch the **7-day daily mean temperatures** using public APIs:

- **Open-Meteo API** – free, no API key required  
- **Nominatim / OpenStreetMap** – converts city names into coordinates  

The program then analyzes the data with **NumPy** to provide:

- Highest and lowest temperatures
- Average temperature
- Temperatures converted to Fahrenheit
- Number of days above 20°C

This project is perfect for learning:

- How to work with public APIs in Python  
- Real-world data analysis with NumPy  
- Handling dynamic user input  

---

## Features

- Accepts **any city worldwide**  
- Fetches **7-day daily mean temperatures**  
- Computes max, min, mean, and Fahrenheit conversions  
- Counts days above 20°C  
- Handles invalid cities and network errors gracefully  
- **No API key required**  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/7-day-weather-analysis.git
cd 7-day-weather-analysis
