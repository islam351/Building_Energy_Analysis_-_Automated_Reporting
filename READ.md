# ⚡ Building Energy Analysis & Automated Reporting

## 📖 Project Overview
This project is a complete, end-to-end data pipeline designed for an **Energy Data Analyst**. It simulates a real-world scenario: managing a portfolio of **50 commercial buildings in France** over a 2-year period (2023-2024), analyzing **3.5 million rows** of 15-minute interval smart meter data.

The goal of this project is to demonstrate the ability to ingest raw data, detect anomalies, forecast future consumption, calculate critical energy KPIs, and deliver actionable business insights through interactive dashboards.

---

## 🎯 Business Problem
Energy managers often rely on manual Excel reports that take days to compile. They struggle to identify energy waste (such as HVAC left on during weekends), cannot predict future demand to optimize purchasing, and lack visibility into their highest-cost facilities (Demand Charges).

## 💡 The Solution
This project builds an automated *Building Energy Analysis & Automated Reporting* that:
1. Detects waste and anomalies using Machine Learning (Isolation Forest).
2. Predicts future consumption using Time-Series Forecasting (Prophet).
3. Calculates critical KPIs like **Load Factor**, **Energy Use Intensity (EUI)**, and **Demand Charges**.
4. Visualizes portfolio performance in an executive Power BI dashboard.

---

## 🛠️ Tech Stack & Tools
*   **Database:** PostgreSQL (Relational database for 8 interconnected tables).
*   **Data Analysis:** Python (Pandas, NumPy, Matplotlib).
*   **Machine Learning:** Scikit-Learn (Isolation Forest), Prophet (Meta).
*   **Visualization:** Power BI Desktop, Microsoft Excel.
*   **Version Control:** Git & GitHub.

---

## 📂 Project Structure
```text
energy_intelligence_project1/
│
├── sql/                 # SQL scripts for schema creation and business queries
├── notebooks/           # Python Jupyter Notebooks for the data pipeline
├── outputs/             # Auto-generated Excel reports and chart images
├── PowerBi/             # Screenshots of the Power BI Dashboard
└── README.md            # Project documentation