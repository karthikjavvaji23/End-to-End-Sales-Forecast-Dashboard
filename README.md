# 📊 Superstore Sales Forecasting Dashboard

**Power BI + Prophet ML | Sales Analytics & Forecasting**

Forecasting has always felt like a *superpower* — the ability to understand past patterns and predict what happens next. In this project, I built a complete **Retail Sales Forecast & Performance Dashboard** from scratch using the **Kaggle Superstore dataset**, combining Power BI, DAX, and Prophet machine learning to deliver clear, data-driven sales insights.

---
<img width="1288" height="730" alt="Screenshot 2025-11-27 004729" src="https://github.com/user-attachments/assets/48e44e13-4f5e-417f-92b1-abec76ca6672" />

## 🔍 Project Objective

The goal was to answer key business questions such as:

* How did sales perform this year?
* Which categories contribute the most revenue?
* What are the strongest and weakest months?
* How accurate is the forecast compared to actuals?
* What can we expect for next year's sales?

By blending **actual sales**, **Prophet-generated forecasts**, and **dynamic Power BI visuals**, the dashboard provides a complete view of historical performance and future expectations.

---

## 🧱 What I Built

### **✔ End-to-End Data Pipeline**

* Cleaned and transformed the Superstore dataset
* Created a custom forecasting table with Actuals, Forecasts & Confidence Intervals
* Exported Prophet ML results into Power BI
* Built DAX measures for YoY Growth, Forecast Accuracy, Next-Year Forecast, and Error %

### **✔ Interactive Power BI Dashboard**

Includes:

* **KPI Cards:**
  Actual Sales, Forecasted Sales, Next-Year Forecast, YoY Forecast Growth %, Forecast Accuracy

* **Visuals:**

  * Actual vs Forecast Trend Line
  * Sales by Category
  * Seasonality Heatmap (Month × Year)
  * Top Performing Months
  * Forecast Trend Overview
  * Dynamic Narrative that updates with slicers

* **Filters:**

  * Year slicer for instant switching between years
  * All visuals react dynamically to selections

---

## 🤖 Forecasting Approach (Prophet ML)

Prophet was used to model historical sales and generate future predictions:

1. Aggregated monthly sales
2. Trained Prophet on historical data
3. Generated forecasts + upper/lower confidence bounds
4. Exported results into Power BI
5. Built visuals comparing Actual vs Forecast
6. Calculated forecast error & accuracy metrics

This blend of ML + BI enables stronger and more reliable business insights.

---

## 🏢 Business Value

This dashboard can support key business decisions:

* **Demand planning & budgeting**
* **Inventory and staffing optimization**
* **Category performance tracking**
* **Identifying seasonal peaks & dips**
* **Measuring forecast reliability**
* **Detecting early trends or anomalies**

It turns raw data into a practical, executive-ready view of sales performance.

---

## 📂 Repository Structure

```
dashboards/
  Superstore_Forecasting.pbix

data/
  raw/
    Superstore.csv
  processed/
    Superstore_clean.csv
    customer_segments.csv
    inventory_metrics.csv
    sales_forecast.csv

notebooks/
  prophet_sales_forecasting.ipynb
  1_eda.ipynb

images/
  dashboard_overview.png
  kpi_section.png
  forecast_trend.png
```

---

## 🧠 Skills Used

* Power BI (DAX, modeling, dashboard design)
* Time Series Forecasting (Prophet ML)
* Python (data prep & forecasting logic)
* Data Cleaning & Transformation
* Sales Analytics & Business Intelligence
* Data Visualization & Storytelling

---

## 📸 Dashboard Preview

*(Add your screenshots here after uploading images)*

```md
![Dashboard Overview](images/dashboard_overview.png)
```
