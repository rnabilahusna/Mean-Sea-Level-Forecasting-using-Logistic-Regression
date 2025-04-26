# 🌊 Change in Mean Sea Levels

Sea level rise is one of the main indicators of climate change. It has been rising at approximately **3.3 millimeters per year** since the early 1990s (the beginning of satellite records, according to the Copernicus Marine Ocean Monitoring Indicator catalogue).  
New calculations from the **Fourth Ocean State Report** reveal that sea level rise is accelerating, increasing by **0.12 ± 0.073 mm/year** annually.

This project analyzes the **"Change in Mean Sea Levels"** dataset to explore global and regional sea level trends, detect anomalies, and forecast future changes.

---

## 📂 Dataset

- **Name**: Change in Mean Sea Levels  
- **Source**: International Monetary Fund (IMF), 2020 - Laboratory for Satellite Altimetry  
- **Overview**: The dataset contains mean sea level variations over time across different global regions.

---

## ❓ Research Questions

### 🔮 Forecasting
- What are the predicted mean sea levels for specific regions or globally, looking 25 years ahead?

### ⚠️ Anomaly Detection
- How can we identify unusual or extreme sea level values that may serve as indicators of anomalies, storms, or floods?

### 📅 Seasonal Patterns
- What are the characteristics of annual cycles in sea level changes, and how do they vary over time?

---

## 🔍 Project Workflow

### 1. Data Selection
- Loaded and explored the Change in Mean Sea Levels dataset.  
- **Source**: International Monetary Fund (IMF), 2020.

### 2. Data Cleaning and Preparation
- Dropped irrelevant and missing columns (e.g., `ISO2`, `ISO3`, `Source`, etc.).
- Standardized date format and split into `Year`, `Month`, and `Day`.
- Handled missing values and checked for duplicates.
- Lowercased unit values and renamed columns for clarity.
- Sorted data by `Value` and `Date`.
- Discretized `Value` into bins for better distribution analysis.

### 3. Data Aggregation
- Calculated **annual mean sea level changes**.
- Calculated **regional mean sea level variations**.
- Created **global mean sea level time series**.

### 4. Data Visualization
- Distribution of sea level values globally and for specific regions (e.g., **Baltic Sea**).
- Global trend of sea level rise from **1992 to 2022**.
- **Annual mean sea level** bar plots.
- **Regional variation** in mean sea levels.

### 5. Machine Learning Implementation
- Used **Linear Regression** to forecast mean sea levels.
- Predicted sea levels **5–25 years** into the future based on historical data.

---

## 🛠 Tech Stack

- **Language**: Python  
- **Libraries**:
  - `pandas` (Data manipulation)
  - `numpy` (Numerical computation)
  - `matplotlib` (Visualization)
  - `scikit-learn` (Machine learning models: Linear Regression, KMeans, Isolation Forest)

---

## 📊 Key Insights

- The **global sea level** shows a consistent **rising trend**.
- **Baltic Sea** had both the highest and lowest recorded mean sea levels but showed a **normal distribution** pattern.
- **Annual cycle analysis** reveals a yearly rise in mean sea level, likely driven by **global warming and glacier melting**.
- Forecasting suggests that sea level rise will continue to **accelerate** if current environmental conditions persist.

---

## 🔮 Future Work

- Apply more complex models (e.g., **ARIMA**, **LSTM**) for improved time series forecasting.
- Incorporate **external environmental factors** (temperature, CO₂ levels) for multivariate analysis.
- Create **interactive dashboards** (using **Plotly** or **Tableau**) for dynamic visualizations.

---

## 📑 References

- International Monetary Fund (IMF), 2020 - Laboratory for Satellite Altimetry  
- Copernicus Marine Ocean Monitoring Indicator catalogue  
- Fourth Ocean State Report

---
