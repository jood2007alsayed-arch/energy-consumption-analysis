#  Daily Energy Consumption & Performance Optimization Analysis

## 📌 Project Overview
This project focuses on analyzing daily energy consumption patterns over a two-year period, identifying long-term trends and seasonality. Furthermore, it implements large-scale data engineering best practices in Python to optimize memory usage and storage efficiency.

---

## 🛠️ Tech Stack & Skills
- **Language: ** Python
- **Libraries: ** Pandas, NumPy, Matplotlib
- **Core Concepts: ** Time Series Analysis, Daily Resampling & Linear Interpolation, Rolling Statistics, Memory Down casting, Chunk Processing, Parquet Optimization.

---

## 🔍 Key Findings & Insights
1. **Seasonal Trends: ** Daily energy consumption shows a strong seasonal pattern, rising progressively from January and peaking in mid-year (July) before declining toward winter.
2. **Weekly Seasonality: ** Weekday energy consumption remains consistently higher compared to weekends.
3. **Memory Optimization: ** Reduced dataset memory usage from **66.74 MB to 7.15 MB** (~89% reduction) through numerical down casting and category encoding.
4. **Storage Efficiency: ** Transitioned large CSV files into chunk-processed **Parquet** format, decreasing storage footprint from **15.06 MB to 4.55 MB**.

