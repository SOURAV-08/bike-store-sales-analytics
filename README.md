# bike-store-sales-analytics

# 🚲 Bike Store Sales Analytics Dashboard
**An End-to-End Data Pipeline: PostgreSQL ➔ Python ➔ Streamlit**

## 📌 Project Overview
This project is a comprehensive Business Intelligence solution designed to analyze retail performance for a multi-location bike store. It automates the process of extracting data from a relational database and visualizing key business metrics through an interactive web interface.

## 🚀 Features
* **Live Database Connection:** Real-time data retrieval from a PostgreSQL backend.
* **Dynamic Visualizations:** Interactive bar charts and donut charts built with Plotly.
* **Multi-Metric Tracking:** * Revenue breakdown by Brand.
    * Sales volume by Product Category.
    * Performance comparison across Store Locations.
* **Professional UI:** Sidebar system status and side-by-side data tables for granular analysis.

## 🛠️ Technical Stack
* **Database:** PostgreSQL (Star Schema design)
* **Language:** Python 3.14
* **Libraries:** Pandas, Psycopg2, Plotly Express
* **Web Framework:** Streamlit
* **Environment:** macOS / VS Code / Virtual Environments (.venv)

## 📂 Project Structure
```text
├── dashboard.py          # Main Streamlit application code
├── .venv/                # Python virtual environment
├── SQL_Queries/          # Folder containing .sql scripts for database setup
├── Bike_Store_Report.pdf # Comprehensive technical project report
└── README.md             # Project documentation
