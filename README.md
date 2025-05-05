# 🌍 Global Temperature Change Prediction

This project aims to **analyze and forecast global land temperature changes** using historical climate data. It dives deep into city-level temperature trends, forecasts future changes, and explores the correlation between temperature, pollution, and greenhouse gas emissions.

## 📌 Objectives

1. **Forecast Future Temperatures**  
   Using time series models like ARIMA, we forecast temperature trends for major cities such as New York.

2. **Identify Top 10 U.S. Cities with Maximum Temperature Change**  
   This section highlights cities that are seeing the most significant warming.

3. **Analyze Impact of Pollution and Greenhouse Gases**  
   Correlation analysis is used to examine how emissions and pollutants influence temperature rise, with a focus on New York.

---

## 📂 Datasets Used

- **Global Land Temperatures by City**  
  Source: [Kaggle - Berkeley Earth](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)

- **U.S. Pollution Data**  
  Source: [Kaggle - US Pollution](https://www.kaggle.com/sogun3/uspollution/data)

- **International Greenhouse Gas Emissions**  
  Source: [Kaggle - UN Emissions Data](https://www.kaggle.com/unitednations/international-greenhouse-gas-emissions)

---

## 🧠 Techniques & Libraries

- **Time Series Analysis** (Stationarity check, ACF, PACF, ARIMA modeling)
- **Data Preprocessing & Wrangling** with `pandas`
- **Visualization** using `matplotlib`, `seaborn`, and `plotly`
- **Correlation Analysis** for impact assessment
- **Widgets & Interactivity** for user selection of cities

---

## 🔍 Key Insights

- Future summers are projected to become cooler while winters get warmer in some regions (e.g., New York).
- HCFCs were identified as the strongest contributors to temperature increases.
- The temperature patterns across cities show varied sensitivity to environmental factors.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/global-temp-prediction.git
   cd global-temp-prediction
