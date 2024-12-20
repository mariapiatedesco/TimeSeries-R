# Time Series Analysis

This repository contains the materials, code, and analysis for the **Time Series Analysis Project**, focused on analyzing the macroeconomic indicators of Italy over time. 

---

## ⚠️ Disclaimer
The report and code comments are written in **Italian**. If needed, feel free to reach out to me for clarification or translation.

---

## 📘 Project Overview

- **Course**: Time Series Lab
- **Academic year**: 2022/2023
- **Data Source**: The datasets were retrieved from the **FRED (Federal Reserve Economic Data)** portal ([FRED](https://fred.stlouisfed.org)).
- **Time Frame**: The analysis spans from the first quarter of 1996 to the fourth quarter of 2022.

---

## 🔧 Technologies Used

- **R**: Primary programming language for analysis.
- **Libraries**:
  - `forecast`, `quantmod`, `GGally`, `tidyverse`, `dygraphs`: For data manipulation, visualization, and modeling.
---

## 🏗️ Repository Structure

- `TimeSeries.html`: To correctly read the html file, you can download it and open it using Google, Safari or your preferred browser. 
- `PDFversion.pdf`: A pdf perdion, in case you do not want to the html file.

---

## 🚀 Key Components

### 1. **Data Cleaning and Visualization**
   - Detection and replacement of outliers using robust STL decomposition.
   - Comparison of original and cleaned series to evaluate the impact of anomalies (e.g., COVID-19 disruptions).

### 2. **Time Series Decomposition**
   - Application of STL decomposition to isolate trend, seasonality, and residuals.
   - Quantification of the strength of trend and seasonality components.

### 3. **Forecasting Models**
   - **Benchmark Models**: Includes naive, seasonal naive, mean, and drift methods.
   - **Smoothing Splines**: Implementation of cubic smoothing splines to capture complex trends.
   - **Multiple Linear Regression**: Incorporates additional macroeconomic indicators like exports, imports, and inflation for forecasting GDP.

### 4. **Residual Analysis**
   - Assessment of residuals for normality, autocorrelation, and variance.
   - Validation of model assumptions for reliable forecasting.

