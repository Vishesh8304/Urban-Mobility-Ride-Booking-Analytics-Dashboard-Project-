# 📊 Urban Mobility Ride Booking & Demand Analytics Dashboard

> **Data-Driven Insights & Interactive Excel Dashboard.**

This project focuses on analyzing over 130,000 ride-booking records in the National Capital Region (NCR) to identify growth opportunities, optimize operations, and reduce revenue leakage. By transforming massive raw data into an interactive Excel dashboard, this analysis provides actionable business intelligence for better decision-making.

---

## 📂 Dataset
The dataset used in this project is uploaded in this repository.  

📌 [**Download Dataset (CSV)**](./Urban%20Ride%20Booking%20(NCR)%20Dataset%20.csv)

---

## 🛠️ Data Cleaning & Preparation
Steps performed during preprocessing:

- 🗑️ Removed duplicate **Booking IDs**  
- 📆 Converted **Date-Time** columns into proper formats  
- 🔢 Corrected numeric formatting for revenue/wait time  
- ➕ Created derived columns: `Month`, `Day` using `TEXT()` function  
- 📋 Structured into **Excel Table** for smooth analysis  

---

## 📊 Analysis & Modeling
Pivot Tables + Excel formulas used to create insights:

- 📈 **Business Trend Analysis** (Monthly & Weekly)  
- ❌ **Cancelled Rides Breakdown** (Top reasons)  
- ⚠️ **Incomplete Rides** – operational issues  
- 🚖 **Vehicle Type Analysis** (Auto, Car, Bike)  
- 📍 **Top Pickup Locations**  
- 👤 **Top Customers by Revenue**  

---

## 🖼️ Dashboard Preview
![Dashboard](./Dashboard.jpg)

---

## 🔑 Key Insights
- 💰 **Total Booking Revenue:** 51.4M  
- 🏢 **Company Realized Revenue:** 46.9M  
- ❌ **~55K rides cancelled** → ~5M revenue loss  
- ⏳ **Avg CTAT:** 29 mins → reduces driver utilization  
- 🚖 **Auto rides highest demand** → fleet expansion required  
- 📍 Identified **top 10 pickup hotspots**  
- 👤 Highlighted **loyal/high-value customers**  

---
## 📈 Key Findings & Insights

### 1. Market Analysis: Auto Dominance
*   **Highest Demand:** The **Auto** segment is the leading revenue contributor at **₹12.78M**.
*   **Strategic Insight:** Auto and Mini segments represent over 45% of the total booking value. Expanding the Auto fleet presents the most significant opportunity for capturing more market share.

### 2. Cancellation Analysis: Revenue Leakage
*   **Estimated Revenue Loss:** Approximately **₹5.0M** is lost due to cancellations.
*   **Driver Behavior:** Top issues include "Driver asked to cancel" and "Driver not moving towards pickup."
*   **Location Issues:** Wrong addresses or pickup location mismatches are major contributors to customer-side cancellations.

### 3. Operational Efficiency: Wait Time Analysis
*   **Avg. CTAT (Customer Turnaround Time):** 29.2 mins. High wait times lead to customer frustration and lower retention.
*   **Avg. VTAT (Vehicle Turnaround Time):** 8.5 mins. Drivers respond efficiently once a booking is accepted.
*   **Target:** Optimize dispatch logic to reduce CTAT below 20 minutes for better utilization.

### 4. Top Pickup Hotspots
Highest demand locations identified:
*   **AIIMS**
*   **Badarpur**
*   **Dwarka**
---
## 📊 Key Business Metrics (KPIs)

| Metric | Value | Description |
| :--- | :--- | :--- |
| **Total Revenue** | ₹51.4M | Total booking value across all categories. |
| **Success Revenue** | ₹46.9M | Actual revenue realized from completed rides. |
| **Total Bookings** | 148.8K | Massive scale of records analyzed. |
| **Avg. Rating** | 4.4 / 5 | High customer satisfaction despite operational challenges. |

---
## ✅ Recommendations
- 🚨 Reduce **cancellations** to prevent heavy revenue loss  
- ⏳ Optimize **CTAT** for better customer experience  
- 🚖 Increase **Auto fleet size** to meet demand  
- 📊 Align **vehicle supply with customer demand**  
- 🔍 Regular monitoring via dashboard for strategic growth  

---

## 🚀 Tech Stack
- **Microsoft Excel** → Data Cleaning, Analysis, Dashboarding  
- **Pivot Tables & Charts** → Interactive visuals  
- **Excel Formulas** → Derived metrics & insights  

---
