# 🚲 Bike Rental Demand Analysis

![Excel](https://img.shields.io/badge/Tool-Excel-green)
![Data Analysis](https://img.shields.io/badge/Domain-Data%20Analysis-blue)
![Dashboard](https://img.shields.io/badge/Project-Dashboard-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Project Overview

This project focuses on analyzing rental bike sharing data to uncover patterns in **usage behavior, weather impact, and demand trends**. The goal is to derive favourable insights that can help optimize bike availability and improve efficiency.

---

## 📊 Dataset Description

The project uses multiple datasets which were processed and combined to create a final analytical dataset:

* **Dataset_1_YS**

  * 610 rows, 10 columns
* **Dataset_2_YS**

  * 610 rows, 8 columns
* **Dataset_3_YS**

  * 390 rows, 16 columns

---

## 🔗 Data Processing Steps

### 1. Merging Datasets

* Dataset_1 and Dataset_2 were merged
* Result: **Dataset_Merge_YS_v1.1**
* 610 rows, 16 columns

### 2. Appending Data

* Dataset_3 appended to merged dataset
* Result: **Dataset_Final_YS_v1.2**
* 1000 rows, 16 columns

### 3. Feature Engineering

* Created new columns:

  * Time_Slot (Morning, Afternoon, Evening, Night)
  * Time (where it converted "Hour" Column into AM/PM format)
  * Day_Type (Weekday / Weekend)
  * Weather_Type (Readable categories)
* Removed unnecessary fields like "Season" and "Year"

👉 Final Dataset:
**1000 rows (excluding header), 19 columns**

---

## 📈 Key Analysis Performed

### 🔹 Descriptive Analysis

* Mean, Standard Deviation, Min, Max
* Identified variability in rental demand

---

### 🔹 Exploratory Data Analysis (EDA)

* Time-based trends (Hourly/Slot-wise, Daily)
* Weather impact on demand
* User segmentation (Casual vs Registered)

---

### 🔹 Pivot Tables & Charts

* Rentals vs Weather Conditions
* Rentals vs Time Slots
* User Type Distribution
* Daily Demand Trends
* Weekday Demand Trends
* Weekends & Holidays based Rentals
* Weather vs Time vs Rentals
  

---

### 🔹 Statistical Analysis

* COUNTIF / SUMIF → Aggregations
* STDEV → Demand variability
* CORREL → Relationships between variables

---

### 🔹 Visualizations

* 📈 Line Charts → Demand trends
* 📊 Bar Charts → Weather & user analysis
* 🔥 Heatmaps → Time vs Day patterns as well as Time vs Humidity & Temperature vs Weather
* ⚡ Scatter Plots → Temp vs Rentals / Humidity vs Rentals /Windspeed vs Rentals
* 🥧 Pie Chart → User contribution

---

### 🔹 Advanced Analysis

* Correlation Matrix (Heatmap)
* Forecasting (Excel Forecast Sheet)
* Anomaly Detection - (Only 3 anomaly detected while referencing the trend sheet)

---

## 📊 Key Insights

* 🚀 Peak demand occurs during **evening hours**
* 👥 **Registered users dominate** usage
* 🌤️ Weather significantly impacts rentals
* 📈 Demand shows **high variability**
* 🌡️ Temperature has a **positive correlation**
* 💧 Humidity negatively affects demand

---

## 📌 Dashboard Features

* KPI Cards (Total Rentals, Avg Rentals, Peak Time, Best Weather)
* Line Chart (Trend Analysis)
* Weather Impact Chart
* User Distribution Chart
* Heatmap (Time Slot vs Day)
* Interactive Slicers (Weather, Time Slot, Day Type)
* Timeline (Date filtering)

---

## 📽️ Presentation

**Project_One_YS**

* Final presentation showcasing:

  * Usage patterns
  * Weather impact
  * User behavior
  * Forecast insights

---

## 🛠️ Tools & Technologies

* Microsoft Excel

  * Pivot Tables
  * Pivot Charts
  * Conditional Formatting
  * Slicers & Timelines
  * Forecast Sheet

---

## 🎯 Conclusion

The analysis highlights how **time, weather, and user type** influence bike rental demand. These insights support:

* Demand forecasting
* Resource allocation
* Operational planning

---

## 🚀 Future Improvements

* Power BI Dashboard Integration
* Machine Learning Models
* Real-time Analytics

---

## 👤 Author

* *Yousuf S. R. Sakkaf*

---

## ⭐ If you found this project useful, consider it for evaluation!
