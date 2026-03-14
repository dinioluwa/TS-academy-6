# TS-academy-6
# Airline Passenger Forecasting — Time Series

## Overview
This project analyses and forecasts monthly international airline passenger numbers using classical time series techniques. The dataset contains 12 years of monthly data (1949–1960) and exhibits both trend and seasonality, making it ideal for SARIMA-based forecasting.

---

##  Dataset
- **Source:** Airline Dataset
- **Period:** January 1949 – December 1960
- **Frequency:** Monthly
- **Rows:** 144 entries
- **Features:** 1 column

| Column | Description | Type |
|---|---|---|
| `#Passengers` | Monthly count of international airline passengers | int64 |

---

##  Objectives
- Explore and visualise trends and seasonal patterns in airline passenger data
- Test for stationarity using the ADF (Augmented Dickey-Fuller) test
- Apply differencing and transformations to achieve stationarity
- Build and tune a SARIMA model for forecasting
- Evaluate model performance and forecast future passenger numbers

---

##  Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and time series handling |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualisation |
| Statsmodels | SARIMA modelling, ACF/PACF plots, ADF test |
| Jupyter Notebook | Development environment |

---

##  Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
- Line plot of passenger counts over time
- Rolling mean and standard deviation
- Identifying trend and seasonal patterns

### 2. Stationarity Testing
- ADF (Augmented Dickey-Fuller) test
- Log transformation to stabilise variance
- First-order and seasonal differencing

### 3. ACF & PACF Analysis
- Identifying AR and MA orders from ACF/PACF plots
- Determining seasonal AR and MA orders

### 4. SARIMA Modelling
- Model: SARIMA(p,d,q)(P,D,Q)[12]
  

### 5. Forecasting
- In-sample fit evaluation
- Out-of-sample forecasting

---
