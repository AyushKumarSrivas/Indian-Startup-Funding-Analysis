# Indian-Startup-Funding-Analysis
"Exploratory Data Analysis (EDA) of Indian startup funding trends, highlighting top sectors, cities, investors, and yearly funding patterns using Python, Pandas, Matplotlib, and Seaborn."
# Indian Startup Funding Analysis

👨‍💻 **Author:** Ayush Kumar Srivas
🗂️ **Repository:** Indian_Startup_Funding_Analysis

---

## 🧩 Overview

The Indian Startup Funding Analysis project provides a detailed **Exploratory Data Analysis (EDA)** of startup investments in India over the years. The goal is to understand trends in funding, identify top sectors and cities, and highlight the most active investors.

This project is built using Python and focuses on **data cleaning, visualization, and deriving actionable business insights** from startup funding data.

---

## 🧠 Objectives

* Perform EDA to understand funding trends in the Indian startup ecosystem.
* Identify top-funded sectors and average funding per sector.
* Analyze city-wise funding distribution.
* Find the most active investors.
* Use visualizations to present insights clearly and effectively.
* Derive actionable business insights for investors and startups.

---

## 📊 Dataset Description

The dataset contains information about Indian startup funding, including:

| Feature           | Description                                     |
| ----------------- | ----------------------------------------------- |
| Startup Name      | Name of the startup                             |
| Industry Vertical | Sector or industry of the startup               |
| SubVertical       | Sub-category of the industry                    |
| City / Location   | City where the startup is based                 |
| Investors Name    | Investors funding the startup                   |
| Investment Type   | Type of investment (Seed, Private Equity, etc.) |
| Amount            | Funding amount in INR                           |
| Date              | Date of funding                                 |
| Remarks           | Additional notes                                |

> **Note:** The dataset was pre-processed to handle missing values, convert funding amounts to numeric format, and clean inconsistent column names.

---

## 🧰 Libraries Used

* **Python 3.x**
* **Pandas, NumPy** → Data cleaning and manipulation
* **Matplotlib, Seaborn** → Data visualization and plotting
* **Jupyter Notebook** → Project environment

---

## 📈 Exploratory Data Analysis (EDA)

EDA was conducted to identify trends, patterns, and relationships in the startup funding data.

### 🔍 Key EDA Steps

* Checked data types, missing values, and cleaned inconsistent entries.
* Converted funding amounts into numeric values.
* Extracted the funding year from the date column.
* Visualized funding trends over the years.
* Identified top-funded sectors and average funding by sector.
* Analyzed city-wise funding and top investors.
* Created advanced visualizations like heatmaps, pie charts, and distribution plots.

### 🧠 Insights from EDA

* India saw a significant surge in startup funding post-2015.
* **FinTech, EdTech, and E-commerce** are the top-funded sectors.
* **Bengaluru, Delhi NCR, and Mumbai** dominate funding distribution.
* **Sequoia Capital, Tiger Global, and Accel Partners** are the most active investors.
* Long-term trends show technology and innovative sectors receiving the highest average funding.
* COVID-19 (2020) caused a dip, but funding rebounded in 2021.
* Top startups like **Byju's, OYO, and Paytm** dominate total funding charts.

---

## ⚙️ Data Preprocessing Steps

### Handling Missing Values

Filled or removed null values in key columns.

### Cleaning Columns

Removed spaces, special characters, and standardized column names for consistency.

### Converting Amounts

Converted funding amounts to numeric INR values (handling Crores, Lakhs, Millions).

### Extracting Year

Parsed the date column to extract the funding year for trend analysis.

---

## 🤖 Visualizations & Analysis

* **Year-wise Total Funding** → Line plot showing funding trends.
* **Top 10 Most Funded Sectors** → Bar chart.
* **Top Funded Cities** → Bar chart.
* **Top 10 Most Active Investors** → Bar chart.
* **Average Funding by Sector** → Bar chart.
* **Funding Distribution** → Histogram with KDE.
* **Top 5 Startups by Funding** → Bar chart.
* **Sector Funding Over Years** → Heatmap.
* **Top 5 Cities Funding Share** → Pie chart.
* **Correlation Heatmap** → Year vs Funding Amount.

---

## 💡 Outcome

This project demonstrates strong skills in **data cleaning, EDA, visualization, and deriving business insights**. It is an excellent portfolio project for **Data Analyst, Business Intelligence, and Investment Analyst roles**, showing practical application of Python and data visualization in real-world startup funding analysis.
