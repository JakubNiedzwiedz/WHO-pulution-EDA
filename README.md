# 🌍 Air Pollution EDA (WHO Dataset)

Exploratory Data Analysis (EDA) of global air pollution data from the World Health Organization (WHO), including statistical analysis and geospatial visualization at the level of regions, countries, and cities.

---

## 📊 Project Overview

The goal of this project is to explore global air pollution patterns using WHO data and to analyze differences across multiple levels of aggregation:
- 🌐 Regions (WHO regions)
- 🏳️ Countries
- 🏙️ Cities

The project includes both statistical analysis and interactive visualizations, with a particular focus on spatial distribution of pollutants.

---

## 📁 Dataset

Source: World Health Organization (WHO)

The dataset contains measurements from multiple locations worldwide, including:

- **Measurement Year** – year of observation  
- **PM2.5 (μg/m3)** – fine particulate matter concentration  
- **PM10 (μg/m3)** – coarse particulate matter concentration  
- **NO2 (μg/m3)** – nitrogen dioxide concentration  
- **Temporal coverage (%)** – data completeness indicators  
- **Country / City / Region information**  

Additionally, an external dataset (`worldcities`) was used to obtain geographical coordinates for cities.

---

## 🔧 Tools & Technologies

- Python 🐍  
- Pandas – data processing  
- Plotly – interactive visualizations  
- Matplotlib / Seaborn – statistical plots  
- ITables – interactive data inspection  
- ipywidgets – interactive controls  
- Jupyter Notebook / VS Code  

---

## 📈 Exploratory Data Analysis (EDA)

The analysis includes:

### 🔹 Data preparation
- Data cleaning and type conversion  
- Handling missing values  
- Standardization of city names  

### 🔹 Analysis by aggregation level
- **Region level** – average pollution levels, variability, exceedances  
- **Country level** – rankings, trends, variability across cities  
- **City level** – correlations, extreme values, time trends  

### 🔹 Statistical insights
- Correlation analysis between pollutants  
- Coefficient of variation across aggregation levels  
- Distribution analysis (mean, median, IQR)

---

## 🗺️ Geospatial Analysis

### 🌐 Country-level map
- Choropleth map showing median pollution levels per country  
- Interactive filtering by pollutant and year  

### 🏙️ City-level map
- Interactive point-based map using geographic coordinates  
- Color represents pollution level  
- Filters:
  - pollutant (PM2.5, PM10, NO2)
  - year
  - WHO region  

### 📍 Geocoding approach
City coordinates were assigned using the `worldcities` dataset:
- primary matching: **ISO3 + city name**
- fallback strategies and manual corrections applied  

---

## ⚠️ Limitations

- Not all cities could be matched to geographic coordinates  
- Differences in naming conventions
- Some locations required manual normalization  
- Spatial coverage is high but not complete  

---

## 🤖 Machine Learning Potential


---

## 📌 Key Insights



## 👤 Authors

Jakub Niedźwiedź
Oliwier Kolbusz
Roksana Jandura
(PUM Project - Group 9)

---

## 📜 License

This project is for educational purposes.