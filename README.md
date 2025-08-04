# 📈 Brent Oil Price Change Point Analysis

This repository contains a structured analysis of Brent crude oil prices to detect structural changes and associate them with major geopolitical and economic events. It combines classical time series exploration with Bayesian change point detection.

---

## 🚀 Objectives

- Analyze trends, volatility, and structural shifts in Brent crude oil prices.
- Identify significant change points using Bayesian modeling.
- Associate those points with real-world events (e.g., OPEC decisions, wars, pandemics).
- Quantify the impact of each event-driven structural change.

---

## 🗂️ Project Structure
brent-oil-analysis/
├── data/
│ ├── brent_oil_prices.csv # Daily Brent oil prices
├── notebooks/
│ └── exploratory_analysis.ipynb # EDA and transformation
├── scripts/
├── visuals/
│ ├── brent_trend.png
│ └── change_points_plot.png
└── README.md
## 📊 Exploratory Analysis

- **Trend**: Brent oil prices exhibit long-term upward and downward trends with abrupt changes due to external shocks.


## 🔍 Change Point Modeling (PyMC3)

- **Model Type**: Bayesian change point model with PyMC3.
- **Transformation**: Log returns used for stationarity and volatility analysis.
- **Change Point**: Estimated using a discrete uniform prior over the time series index.
- **Posterior Inference**:
  - Switch date identified with a sharp peak in the posterior distribution.
  - Distinct shifts in mean log returns before and after the change.

