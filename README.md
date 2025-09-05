# Coffee Sales Analysis Dashboard

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-latest-blue)](https://pandas.pydata.org/)  
[![Plotly](https://img.shields.io/badge/Plotly-latest-orange)](https://plotly.com/python/)  
[![Dash](https://img.shields.io/badge/Dash-Plotly-orange)](https://dash.plotly.com/)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---

## Overview

The **Coffee Sales Analysis Dashboard** is an interactive data analysis and visualization tool for coffee shop sales. It provides comprehensive insights into:

- Daily, weekly, and monthly revenue trends
- Popular coffee types and top sellers
- Payment method analysis
- Hourly and weekly sales patterns
- Forecasting of daily, weekly, and monthly sales using ARIMA and Random Forest models

This dashboard is built using **Python**, **Pandas**, **Plotly**, **Dash**, and machine learning models for forecasting.

---

## Features

- **KPI Summary:** Displays total revenue, total transactions, average transaction value, and top-selling coffee.
- **Sales Visualizations:**
  - Daily revenue trend
  - Revenue by coffee type
  - Revenue contribution (Treemap)
  - Payment method breakdown (Pie chart)
  - Hourly and weekly sales heatmaps
  - Coffee popularity trends over time
- **Forecasting:**
  - Daily, weekly, and monthly sales forecasts using ARIMA and Random Forest models
- **Interactive Dashboard:** Built with Dash for a fully interactive web interface.

---

## Installation

1. Clone the repository:
```bash
git clone git@github.com:PanchangniDhangar/coffee-sales-analysis.git
cd coffee-sales-analysis
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
**Required Packages:**

- pandas
- numpy
- plotly
- dash
- statsmodels
- scikit-learn

---

## Usage

1. Ensure your data file `index.csv` is in the project directory.  

2. Run the dashboard:
```yaml
jupyter notebook coffeesales.ipynb
```
3. Open the local server URL (usually `http://127.0.0.1:8050/`) in your browser to interact with the dashboard.

---

## Data

- **index.csv**: Contains coffee sales transactions with columns:
  - `date` / `datetime`: Transaction date and time
  - `coffee_name`: Name of the coffee sold
  - `money`: Revenue for each transaction
  - `cash_type`: Payment method
  - `card`: Customer card identifier

The dashboard processes and aggregates this data for visualization and forecasting.

---

## Forecasting Methodology

- **ARIMA**: Time-series modeling for trend-based forecasts  
- **Random Forest**: Feature-based regression forecasting using historical patterns  
- Forecasts are available at **daily**, **weekly**, and **monthly** granularity.

---

## Visualizations

The dashboard includes:

- Daily, weekly, and monthly sales trends  
- Revenue and sales distribution by coffee type  
- Payment method analysis (pie chart and stacked bar chart)  
- Hourly sales and heatmap of sales by day/hour  
- Coffee popularity trends over time  
- Forecast visualizations with ARIMA and Random Forest for daily, weekly, and monthly sales

---

## Screenshots

<img width="1920" height="2721" alt="screencapture-127-0-0-1-8050-2025-09-05-23_43_06" src="https://github.com/user-attachments/assets/6962ebb2-b0be-467a-ad19-7a445fc85b5c" />

---

## License

This project is licensed under the **MIT License**.

---

## Contributing

Contributions are welcome! Please submit pull requests or open issues for bugs, feature requests, or improvements.

---

## Contact

For any questions or support, reach out to **Panchangni Dhangar** at `panchangnidhangar@gmail.com`.
