# 🌡️ Urban Temperature Trends & Urban Heat Island (UHI) Analysis in Mumbai

## Overview

This project analyzes over 70 years of historical temperature data from Mumbai (1951–2024) to identify long-term climate trends and investigate potential indicators of the Urban Heat Island (UHI) effect.

Using Exploratory Data Analysis (EDA), the study examines changes in maximum and minimum temperatures, seasonal patterns, and extreme heat events to understand how urbanization may be influencing the city's local climate.

---

## 🎯 Project Goals

* Analyze long-term temperature trends in Mumbai
* Study variations in maximum and minimum temperatures
* Explore seasonal and yearly climate patterns
* Identify potential indicators of the Urban Heat Island (UHI) effect
* Generate visual insights from historical climate data

---

## 📊 Dataset

**Dataset:** Mumbai Daily Temperature Data (1951–2024)

### Features

* 📅 Date
* 🌡️ Maximum Temperature
* 🌡️ Minimum Temperature
* 🌧️ Rainfall (where available)

The dataset contains over seven decades of daily climate observations, making it suitable for long-term trend analysis.

---

## 🔬 Methodology

### Data Processing

* Data cleaning and preprocessing
* Handling missing values
* Standardizing date formats

### Feature Engineering

* Extracting year and month
* Calculating mean temperature
* Creating aggregated yearly and monthly metrics

### Exploratory Data Analysis (EDA)

* Trend analysis
* Seasonal pattern analysis
* Heatwave frequency exploration
* Temperature distribution analysis

### Visualization

* Time-series trend plots
* Monthly temperature patterns
* Heatwave occurrence trends
* Comparative climate charts

---

## 📈 Key Visualizations

### Yearly Temperature Trend

Analyzes long-term changes in average temperature across decades.

### Monthly Seasonal Patterns

Explores recurring temperature variations throughout the year.

### Heatwave Frequency Analysis

Tracks changes in the occurrence of extreme temperature events.

---

## 🔍 Key Findings

* 📈 Average temperatures have gradually increased over the past several decades.
* 🌙 Minimum temperatures are rising faster than maximum temperatures.
* ☀️ Seasonal temperature cycles remain relatively consistent.
* 🌧️ Rainfall exhibits moderate influence on temperature variation.
* 🌆 Rising nighttime temperatures suggest potential Urban Heat Island (UHI) effects.

---

## 💡 Insights & Recommendations

* Expand urban green spaces and tree cover.
* Integrate ward-level spatial temperature datasets.
* Compare urban and rural climate trends for stronger UHI validation.
* Develop climate monitoring dashboards for public awareness.
* Support data-driven urban planning and sustainability initiatives.

---

## ⚠️ Limitations

* No ward-level or spatial temperature data available.
* No rural comparison dataset included.
* Analysis focuses on EDA and trend identification.
* UHI indicators are observational and not conclusively validated.

---

## 🚀 Future Enhancements

* 🌍 Geospatial analysis using GIS datasets
* 🤖 Machine learning-based temperature forecasting
* 📊 Interactive dashboards using Streamlit or Power BI
* 🛰️ Satellite imagery integration
* 🏙️ Urban vs. rural comparative climate studies

---

## 📂 Project Structure

```text
urban-temperature-uhi-analysis/
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── data/
│   └── mumbai_temperature_1951_2024.csv
│
├── figures/
│   ├── yearly_trend.png
│   ├── monthly_pattern.png
│   ├── heatwave_trend.png
│
├── README.md
│
└── requirements.txt
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🌍 Impact

Understanding urban temperature trends is essential for climate resilience, sustainable urban planning, and mitigating the impacts of increasing heat stress in rapidly growing cities.

This project contributes toward data-driven approaches for building more sustainable and climate-resilient urban environments.

---

## 📜 License

This project is open-source and available under the MIT License.
