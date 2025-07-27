# 🌾 Two Types of Crop Production in India – A Case Study and Detailed Data Analysis

This repository contains the research work for my MSc Statistics project on **agricultural trends and productivity analysis** in India. The study focuses on two major seasonal crops—**Kharif and Rabi**—and uses statistical tools to understand their production patterns, model future outcomes, and establish insights into irrigation and productivity.

## 📚 Project Summary

### 🎓 Academic Info
- **Submitted by**: Papu Mahanta  
- **Course**: B.Sc. (Sem VI), Statistics  
- **University**: Department of Statistics, Visva-Bharati University  
- **Supervisor**: Dr. Saran Ishika Maiti

### 🧩 Objectives
- Analyze trends in production and productivity of **Kharif and Rabi crops** from **1962 to 2021**
- Apply **Time Series Analysis** techniques: ADF Test, Moving Averages, ACF/PACF, ARIMA, and Holt-Winters models
- Forecast crop production till **2030**
- Study the **relationship between irrigation coverage and total productivity** using **Simple Linear Regression**

---

## 📂 Contents

| File | Description |
|------|-------------|
| `data/crop_production_india.csv` | Raw time series data (1962–2021) |
| `analysis/TimeSeries_Models.R` | All R codes for trend, ARIMA, and Holt-Winters |
| `figures/` | Graphs and charts used in the report |
| `report/Project_Presentation.pdf` | Full presentation slides |
| `README.md` | Project overview and instructions |

---

## 🔍 Methodologies

### 🔹 Data Source
- **Website**: [Indiastat.com](https://www.indiastat.com/table/agriculture/season-wise-area-production-productivity-rice-indi/7264)
- **Variables**:
  - Crop type: Kharif, Rabi
  - Year-wise Production
  - Productivity
  - Percentage Coverage under Irrigation

### 🔹 Tools & Techniques
- 📊 **Descriptive Statistics** (line, bar, pie charts)
- 📈 **Moving Averages** (3, 5, 10 years)
- 🧪 **ADF Test** (Stationarity check)
- 🔁 **Autocorrelation & Partial Autocorrelation** (ACF & PACF)
- 🧮 **ARIMA Models** (MA(1) for Kharif, ARIMA(1,1,2) for Rabi)
- 📉 **Holt-Winters Exponential Smoothing**
- 📐 **Simple Linear Regression** (Irrigation vs. Productivity)

---

## 📊 Forecasts

Using **Holt-Winters**, crop production was forecasted for the years **2021 to 2030**:

| Year | Kharif Production | Rabi Production |
|------|-------------------|------------------|
| 2021 | 106655.1          | 18498.94         |
| 2025 | 115215.9          | 19920.57         |
| 2030 | 125916.8          | 21697.61         |

---

## 📌 Key Findings

- 📈 Both Kharif and Rabi production show an **upward trend**.
- ✅ **Time series data is stationary**, allowing robust forecasting.
- 📉 **ARIMA models** fit the data but have higher RMSE compared to Holt-Winters.
- 🔮 **Holt-Winters model** offers more accurate forecasting.
- 💧 **Irrigation coverage** is **strongly correlated** with productivity (R² = 0.95).

---

## 🛠 Software Used

- **R (R Console & R Studio)**
- **Microsoft Excel** for data visualization
- **MS PowerPoint** & **Adobe Express** for final presentation
- **LaTeX/Word** for documentation

---

## 👨‍🔬 Author

**Papu Mahanta**  
 
🎓 MSc Statistics – Visva-Bharati University

---

## 📖 References

- *Fundamentals of Statistics (Vol 1 & 2)* by Goon, Gupta & Dasgupta  
- Time Series Class Notes by Dr. Saran Ishika Maiti  
- GeeksForGeeks, Wikipedia, Stack Overflow  
- [Indiastat.com](https://www.indiastat.com)

---

> 📌 *This project aims to contribute to agricultural analytics using statistical tools and provides a foundation for forecasting food production patterns in India.*
