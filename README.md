# 🌦️ ETL Weather Data Analysis

This project demonstrates a complete **ETL (Extract, Transform, Load)** workflow for **weather forecasting data**, including **data cleaning**, **analysis**, and **visualization** in Python using a Jupyter Notebook.

---

## 📘 Project Overview

The notebook **`ETL_weather_data.ipynb`** performs the following steps:

1. **Extracts** weather forecast data from an API  
2. **Transforms** it by cleaning, formatting datetime values, and selecting relevant features  
3. **Loads** the data into a structured DataFrame for further analysis  
4. **Visualizes** trends such as temperature changes and weather conditions  

---

## 📊 Example Output

### ✅ Processed Data Sample

The DataFrame includes:
- `datetime` — timestamp of weather data  
- `temp`, `feels_like` — actual and perceived temperatures (°C)  
- `pressure`, `humidity` — atmospheric conditions  
- `weather_main`, `weather_desc` — weather type and description  
- `cloud`, `wind_speed`, `wind_direction` — sky and wind parameters  

---

### 🌡️ Temperature Trend Visualization

The plot shows:
- Temperature changes over time  
- A red dashed line representing the **average temperature**  
- Insights into daily temperature fluctuations  

---

## 🛠️ Technologies Used

- **Python 3.11+**  
- **Jupyter Notebook**  
- **Pandas** — data manipulation  
- **Matplotlib** — data visualization  
- **OpenWeatherMap API

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/astr0q/ETL-OpenWeather-API
   cd ETL-weather-data
