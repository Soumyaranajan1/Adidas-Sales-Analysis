![h-co-NTQteyFDeQY-unsplash](https://github.com/user-attachments/assets/39b211b9-7ce5-4576-9b83-4aa4faa913b1)

# 🛍️ Adidas Sales Analysis Power BI App

An interactive **Power BI dashboard** to analyze Adidas sales performance from 2020 to 2024. This app provides **deep visual insights**, forecasting, and trend analysis across **regions**, **products**, and **timeframes** using dynamic **bookmarks**, slicers, and KPIs.

---

## 📌 Overview

This Power BI project visualizes and analyzes **Adidas US Sales** data using powerful DAX measures, time-series analysis, and predictive visuals. With rich interactivity and user-friendly bookmarks, the dashboard enables quick navigation between key business insights.

---

## 🌟 Features

### 📊 1. **Dashboard Pages**

#### 🔹 **Overview Page**
- KPIs: Total Sales, Profit, Quantity, Returns
- Visuals:
  - Year-wise sales trends
  - Region-wise profit and return comparison
  - Product category distribution

#### 🔹 **Product-Level Insights**
- Top 10 best-selling products
- High-return products by value
- Profit per product category over time

#### 🔹 **Regional Performance**
- Sales and profit across regions
- Region-wise funnel for YoY% contribution
- Scatter or alternative charts (non-map) for quantity

#### 🔹 **Forecast & Trend Analysis**
- Forecasting sales using Power BI analytics
- Waterfall charts for **YoY%** by region
- Trend lines and seasonality exploration

#### 🔹 **Customer & Channel Analysis**
- Sales split by channel (Online vs Offline)
- B2B vs B2C trends
- Customer-centric product performance

---

### 🔖 2. **Bookmarks (Navigation Shortcuts)**

The dashboard includes intuitive **Power BI bookmarks** to allow quick switching between:

- 📍 **Sales Overview**
- 📍 **Regional Funnel View**
- 📍 **YOY Growth Explorer**
- 📍 **Forecasting Panel**
- 📍 **Product Focus**
- 📍 **Returns & Profit Drill-down**

Each bookmark preserves filter states, helping business users explore insights without resetting their context.

---

## 🧠 DAX Measures Used

- `Total Sales`
- `Total Profit`
- `Return %`
- `Quantity Sold`
- `YOY%` (Year-over-Year Growth)
- `MOM%` (Month-over-Month Growth)
- Forecast lines using built-in Power BI analytics

---

## 🧱 Tech Stack

| Tool        | Usage                           |
|-------------|----------------------------------|
| Power BI    | Visualization, DAX, Bookmarks   |
| DAX         | Custom measures, YOY/MOM, KPIs  |
| Power Query | Data cleaning & transformation  |
| Excel/CSV   | Adidas US Sales Dataset (2020–2024) |

---

## 🗂️ File Structure

```plaintext
📁 Adidas-Sales-Analysis/
├── 📊 Adidas_Sales_Analysis.pbix
├── 📂 Dataset/
│   └── adidas_sales_data.csv
├── 📂 Screenshots/
│   ├── overview.png
│   ├── forecast_view.png
│   ├── regional_funnel.png
│   └── product_insights.png
├── 📄 README.md
└── 📄 LICENSE
