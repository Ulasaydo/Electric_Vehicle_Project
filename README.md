# 🚗 Electric Vehicle Market Analysis

An exploratory data analysis and market forecasting project on US Electric Vehicle population data, uncovering adoption trends, manufacturer rankings, range performance, and future market projections.

## 📌 Project Overview

This project analyzes a large-scale EV registration dataset to answer:
- How has EV adoption grown over time, and which years saw the biggest surges?
- Which counties, cities, manufacturers, and models dominate the EV market?
- How does electric range vary across makes, models, and years?
- What does the EV market look like in 2024–2029 based on historical growth?

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-4C72B0)
![SciPy](https://img.shields.io/badge/SciPy-1.11-8CAAE6?logo=scipy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

## 📊 Key Findings

- **EV adoption** has grown sharply since 2016, with **2023 showing the steepest year-over-year increase**
- **King County (Seattle)** leads all regions by a large margin; EV adoption is concentrated in urban centers
- **BEVs (Battery Electric Vehicles) dominate** the market over PHEVs (Plug-in Hybrids)
- **Tesla leads all manufacturers** by a wide margin; Model Y and Model 3 are the top two registered models; Nissan LEAF ranks third
- Electric range has improved significantly over model years, with newer models outperforming older ones
- **Exponential growth model** (SciPy `curve_fit`) projects continued strong EV market expansion through 2029

## 📁 Project Structure
```
Electric_Vehicle_Project/
│
├── Electric_Vehicle_Population_Data.csv   # Raw dataset
└── main.ipynb                             # Full analysis notebook
```

## 🚀 How to Run
```bash
git clone https://github.com/Ulasaydo/Electric_Vehicle_Project.git
cd Electric_Vehicle_Project
pip install pandas matplotlib seaborn scipy jupyter
jupyter notebook main.ipynb
```

## 📈 Methodology

1. **Data Cleaning** — Dropped null values, validated data types
2. **Adoption Trends** — Bar chart of EV registrations by model year
3. **Geographic Analysis** — Top counties and cities by EV registration count
4. **EV Type Distribution** — BEV vs PHEV breakdown (bar + pie chart)
5. **Manufacturer & Model Analysis** — Top 10 makes; top models within top 3 brands
6. **Electric Range Analysis** — Distribution, mean range, range by make/model/year
7. **Market Forecasting** — Exponential growth curve fitted to historical data, projected to 2029

## 👤 Author

**Ulaş Göksu Aydoğdu** — [LinkedIn](https://linkedin.com/in/ulasaydo) · [GitHub](https://github.com/Ulasaydo)
