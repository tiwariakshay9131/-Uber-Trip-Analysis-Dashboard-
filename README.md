# 🚖 Uber Trip Analysis Dashboard – Power BI Project

## 📌 Project Objective

Analyze Uber trip data using **Power BI** to uncover booking trends, revenue insights, and trip efficiency metrics — enabling stakeholders to make data-driven decisions and optimize operations.

---

## 📊 Dashboards Overview

### 🔹 1. Overview Analysis

#### ✅ Key Metrics (KPIs):
- Total Bookings  
- Total Booking Value  
- Average Booking Value  
- Total Trip Distance  
- Average Trip Distance  
- Average Trip Time  

#### 📈 Visual Features:
- **Dynamic Measure Selector** – Choose between Total Bookings, Total Booking Value, and Total Trip Distance using a disconnected table.
- **Vehicle Type Grid Analysis** – Table/Matrix visual with conditional formatting and sorting options.
- **Bookings by Day** – Line or column chart showing daily trends.
- **Breakdown by Payment Type & Trip Type** – Compare card, cash, wallet; day vs night rides.
- **Location-Based Insights:**
  - Most Frequent Pickup & Drop-off Points  
  - Farthest Trip by Distance  
  - Top 5 Locations by Booking Volume  
  - Most Preferred Vehicle per Pickup Location

---

### 🔹 2. Time Analysis Dashboard

Understand trip patterns across different time intervals to optimize pricing and driver availability.

#### 📅 Time-Based Visualizations:
- **Pickup Time (10-Minute Intervals)** – Area Chart
- **Booking Trends by Day Name (Mon–Sun)** – Line Chart
- **Heatmap (Hour vs Day)** – Matrix Grid highlighting peak hours for each day

> All visuals respond to a **Global Dynamic Measure Selector** that filters across dashboards.

---

### 🔹 3. Details Tab (Grid View)

Enable users to explore granular-level trip details.

#### 🧮 Features:
- Grid Table showing key fields (Trip ID, Time, Distance, Booking Value, Vehicle Type, etc.)
- **Drill-Through Functionality** – Right-click to view detailed data from other visuals
- **Bookmark** – Toggle between filtered (drill-through) and full dataset view

---

## 🛠️ Key Features & Enhancements

- 🎛️ Dynamic Titles based on selected KPIs  
- 🔍 Slicers: Filter by Date, City, Payment Type, etc.  
- 🧩 Tooltips with extra insights (Avg Booking Value, Trip Time)  
- 🎨 Conditional Formatting in Grid/Table visuals  
- 🔄 Clear Filters Button  
- 📤 Download Raw Data Button (CSV/Excel – via Power Automate or built-in export)  
- 📖 Bookmark for Data Definitions (explaining KPIs, data sources, refresh frequency)

---

## 💡 Tools & Technologies

- Power BI  
- Power Query  
- DAX  
- Data Modeling  
- Power Automate (for exporting data)

