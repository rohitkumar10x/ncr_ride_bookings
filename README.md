# NCR Ride Booking Analysis

> **Data-Driven Insights & Interactive Excel Dashboard.**

This project focuses on analyzing over 145,000 ride-booking records in the National Capital Region (NCR) to identify growth opportunities, optimize operations, and reduce revenue leakage. By transforming massive raw data into an interactive Excel dashboard, this analysis provides actionable business intelligence for better decision-making.

---

## 📋 Project Overview

### The Goal
The primary objective of this project is to analyze ride-booking trends within the NCR region, identify key factors contributing to cancellations, and pinpoint strategic growth opportunities for fleet expansion.

### The Data
The analysis is based on a comprehensive dataset of **145,000+ booking records**, covering essential metrics such as:
*   **Revenue & Success Revenue**
*   **Cancellations (Driver & Customer side)**
*   **Vehicle Types (Auto, Mini, Prime, etc.)**
*   **Pickup Hotspots**

---

## 📈 Dashboard Visualization

Below is the interactive Excel dashboard developed to provide a holistic view of operational and financial performance:

![NCR Ride Booking Dashboard](https://github.com/rohitkumar10x/ncr_ride_bookings/blob/main/Dashboard.jpg?raw=true)

---

## 🛠️ Technical Tools & Process

### The Tech Stack
*   **Microsoft Excel:** The core platform used for data cleaning, processing, and interactive dashboarding.
*   **Pivot Tables & Charts:** Employed to summarize 145k+ records into dynamic visual summaries.
*   **XLOOKUP & Advanced Formulas:** Used for efficient data retrieval and feature engineering (e.g., extracting Month and Day).
*   **Conditional Formatting:** Utilized to instantly highlight critical operational issues like high wait times or low ratings.

### Data Cleaning & Preparation
To ensure 100% data accuracy, the following steps were taken:
1.  **Removing Noise:** Deleted duplicate Booking IDs and handled missing values.
2.  **Formatting:** Standardized Date-Time columns and corrected numeric formats for revenue and distance.
3.  **Feature Engineering:** Created "Month" and "Day" columns using the `TEXT()` function for granular trend analysis.
4.  **Structuring:** Organized raw data into an Excel Table for seamless integration with Pivot Tables.

---

## 📊 Key Business Metrics (KPIs)

| Metric | Value | Description |
| :--- | :--- | :--- |
| **Total Revenue** | ₹51.4M | Total booking value across all categories. |
| **Success Revenue** | ₹46.9M | Actual revenue realized from completed rides. |
| **Total Bookings** | 148.8K | Massive scale of records analyzed. |
| **Avg. Rating** | 4.4 / 5 | High customer satisfaction despite operational challenges. |

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

## ✅ Strategic Recommendations

*   **Reduce Cancellations:** Implement penalties or incentives to mitigate "Driver asked to cancel" issues and prevent revenue loss.
*   **Fleet Expansion:** Increase the number of Autos to meet the high demand in the NCR region.
*   **Optimize CTAT:** Improve routing and dispatch logic to reduce customer wait times.
*   **Monitor Hotspots:** Position more drivers near high-demand locations like AIIMS and Dwarka to align supply with demand.

---

## 🔮 Future Steps
*   Automating the data pipeline for daily real-time updates.
*   Integrating predictive modeling for demand forecasting to further optimize driver positioning.

---

**Author:** Rohit Kumar | *Data Analyst*
