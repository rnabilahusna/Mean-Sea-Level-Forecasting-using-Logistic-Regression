# 🌊 Change in Mean Sea Levels

Sea level rise is one of the main indicators of climate change, and it has been rising at about **3.3 millimeters per year** since the early 1990s (the beginning of our satellite record, as seen in the Copernicus Marine Ocean Monitoring Indicator catalogue).  
New calculations in the Fourth Ocean State Report reveal that **sea level rise is accelerating**, with the rate increasing by **0.12 ± 0.073 mm/year** each year.

---

## 📚 Dataset Information

- **Dataset**: Change in Mean Sea Levels
- **Source**: [International Monetary Fund (IMF), 2020 - Sea Level Rise, Laboratory for Satellite Altimetry](https://climatedata.imf.org/)

The dataset provides information on the variation in mean sea levels over time across different regions, with observations associated with various indicators, units, and sources.

---

## 🔍 Research Questions

1. **Future Predictions**:  
   What are the predicted mean sea levels for specific regions or globally at future time points, specifically 25 years ahead?
   
2. **Anomaly Detection**:  
   How can we identify unusual or extreme sea level values that may indicate anomalies (e.g., storms, floods)?

3. **Annual Patterns**:  
   What are the patterns and characteristics of annual cycles in sea level changes, and how do they vary over time?

---

## 🗂️ Data Selection

- **Dataset**: Change in Mean Sea Levels
- **Source**: IMF, 2020. Laboratory for Satellite Altimetry.

---

## 🛠️ Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import matplotlib.cm as cm
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.cluster import KMeans
from sklearn.ensemble import IsolationForest
