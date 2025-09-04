# Blinkit Sales Analysis: Excel & Python

This repository provides a comprehensive sales analysis of Blinkit, an Indian quick commerce app. The project is implemented using two distinct approaches: a dynamic **Microsoft Excel Dashboard** and an **Exploratory Data Analysis (EDA) in Python**.

## 📖 Project Overview

The objective is to conduct a detailed analysis of Blinkit's sales performance, customer satisfaction, and distribution channels to provide actionable business insights. Both modules use the same dataset, a replica of real-world sales data with approximately 8,500 rows and 12 columns.

---

## 📊 Interactive Excel Dashboard

An interactive dashboard built in Excel for dynamic data visualisation and analysis.

### Key Features
*   **Dynamic Slicers:** Filter data by `Outlet Size`, `Outlet Location`, and `Item Type`.
*   **KPI Summary:** Tracks **Total Sales**, **Average Sales**, **Number of Items**, and **Average Rating**.
*   **Comprehensive Charts:** Includes donut, bar, line, and funnel charts to analyse sales across various dimensions like `Fat Content`, `Item Type`, and `Outlet Establishment Year`.
*   **Data Cleaning:** The `Item Fat Content` column was standardised using Excel's 'Find and Replace' feature (e.g., 'LF' became 'Low Fat').
*   **Navigation:** Features 'Home' and 'Data' buttons for easy movement between the dashboard, PivotTables, and raw data sheets.

### Tools Used
*   Microsoft Excel (2019+ recommended)
*   PivotTables & PivotCharts
*   Slicers

---

## 🐍 Python Exploratory Data Analysis (EDA)

An EDA project conducted in a Jupyter Notebook using Python to derive statistical insights programmatically.

### Key Features
*   **Data Preprocessing:** Cleaned the `Item Fat Content` column using the `.replace()` function for consistency.
*   **KPI Calculation:** Calculated key business metrics using Pandas functions like `.sum()`, `.mean()`, and `.count()`, displaying them with formatted f-strings.
*   **Data Visualisation:** Created various charts to meet business requirements:
    *   **Pie Chart:** Sales distribution by `Fat Content`.
    *   **Bar Charts:** Total sales by `Item Type` and a side-by-side comparison for `Outlet Location`.
    *   **Line Chart:** Sales trends by `Outlet Establishment Year`.
*   **In-depth Analysis:** Uncovers sales drivers to inform business strategy.

### Tools and Libraries Used
*   **Python** & **Jupyter Notebook**
*   **Pandas:** For data import, cleaning, and manipulation.
*   **NumPy:** For numerical operations.
*   **Matplotlib:** For creating plots like pie, bar, and line charts.
*   **Seaborn:** For advanced statistical visualisations.

### How to Run
1.  Ensure you have Python and Jupyter Notebook installed.
2.  Clone the repository and install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  Place the dataset in the project directory.
4.  Open the `.ipynb` file and update the data path.
5.  It is recommended to restart the kernel and run all cells (`Kernel > Restart & Run All`) for a clean execution.

