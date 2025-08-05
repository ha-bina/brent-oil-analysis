
# Brent Oil Price Analysis Project

This repository provides a comprehensive pipeline for analyzing how major political and economic events influence Brent crude oil prices. The project consists of three main tasks: time series analysis with change point detection, event correlation analysis, and an interactive dashboard application.

---

## Project Structure

```
brent-oil-analysis/
├── data/
│   ├── raw/
│   ├── processed/
│   └── events/
├── notebooks/
│   ├── Task1_TimeSeriesAnalysis.ipynb
│   ├── Task2_EventCorrelation.ipynb
│   └── Task3_DashboardDesign.md
├── src/
│   ├── analysis/
│   ├── models/
│   └── utils/
├── dashboard/
│   ├── backend/ (Flask APIs)
│   └── frontend/ (React app)
├── reports/
│   └── final_report.pdf
├── requirements.txt
└── README.md
```

---

## Task 1: Time Series Analysis and Change Point Detection

Analyze Brent oil price data to identify significant change points using statistical and machine learning approaches. This includes preprocessing, visualizing trends, and applying methods like Bayesian Change Point Detection or Ruptures to isolate periods of abrupt change.

**Deliverables:**
- Preprocessed and cleaned Brent price time series.
- Change points annotated with corresponding dates.
- Visualizations of segmented time periods.

## Task 2: Event Correlation Analysis

Investigate the correlation between major political/economic events and Brent oil price fluctuations. Events include geopolitical conflicts, OPEC decisions, sanctions, and global economic downturns.

**Deliverables:**
- Curated event dataset.
- Event-impact window analysis.
- Statistical summaries and correlation plots showing event-price impact.

## Task 3: Interactive Dashboard for Analysis Results

Build an interactive web dashboard to visualize analysis results, enabling stakeholders to explore trends and understand how specific events influence price shifts.

**Backend (Flask):**
- REST APIs to serve time series, event data, and model outputs.
- Optional: Real-time data integration support.

**Frontend (React):**
- Interactive charts using Recharts or D3.js.
- Filters for date ranges, event types, and statistical indicators.
- Event highlighting to visualize spikes/drops linked to news or events.

**Deliverables:**
- A responsive and informative dashboard for stakeholder exploration.
- Drill-down functionality for inspecting trends around specific events.

---

## summary

- All three tasks leverage time series analytics, correlation modeling, and modern web development to build a full-stack analytical product. Our approach includes temporal segmentation, structured event mapping, and dynamic visualizations.

- strengthen event labeling automation, enrich models with more macroeconomic features, and integrate forecasting modules for proactive decision-making.

- This project offers an actionable framework for understanding Brent oil volatility and guiding investment, energy security policy, and risk management using explainable data-driven tools.

---

## Installation

Clone the repository and install required packages:

```bash
git clone https://github.com/ha-bina/brent-oil-analysis.git
cd brent-oil-analysis
pip install -r requirements.txt
```

For dashboard setup (React + Flask), refer to `dashboard/README.md`.




