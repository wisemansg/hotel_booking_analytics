# 🏨 Hotel Analytics Dashboard 

## 📖 1. Project Overview
This project transforms raw, inconsistent hotel booking data into an interactive **Streamlit web application** hosted directly within **Snowflake**. By leveraging a structured data pipeline, the dashboard provides stakeholders with real-time insights into revenue, booking behaviors, and geographic performance.

## ⚙️ 2. Technical Architecture
The data pipeline follows a structured "Medallion" workflow:
1. **Raw Data:** Initial ingestion of unprocessed files into Snowflake.
2. **Cleaned Data:** Scrubbing for errors, handling nulls, and formatting dates.
3. **Business Ready:** Final "Approved" datasets prepared for analysis.
4. **Streamlit UI:** The visualization layer where data is transformed into interactive charts using Python.

![Architecture Diagram](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/ARCHITECTURE%20DIAGRAM.jpeg)

## ⚡ 3. Live Interaction Features
This dashboard is a fully interactive tool designed for data exploration:
*   **Live Data Sync:** Hosted on Snowflake, ensuring the dashboard reflects the most current data.
*   **Dynamic Filtering:** Users can drill down into specific dates, cities, or room types.
*   **Real-Time KPI Updates:** Metrics recalculate instantly based on user input.

## 📊 4. Full Dashboard & Results
The dashboard provides a high-level executive view of the hotel's performance.

![Full Dashboard](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/FULL%20DASHBOARD.png)

### Executive KPIs

| Metric | Value |
| :--- | :--- |
| **Total Revenue** | 577,347 |
| **Total Bookings** | 1,729 |
| **Total Guests** | 5,072 |
| **Avg. Booking Value** | 334.11 |

### 🔗 Live Interaction
If you have access to the Snowflake environment, you can interact with the live application here:
👉 [Hotel Analytics Live Dashboard](https://app.snowflake.com/streamlit/sweden-central.azure/xf09284/#/apps/3ux4b4y5obk6caso6633)

## 🔍 5. Deep Dive Analysis

### A. Revenue & Booking Trends
![Monthly Revenue Trend](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/MONTHLY%20REVENUE%20TREND.png)

![Monthly Bookings Trend](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/MONTHLY%20BOOKINGS%20TREND.png)

### B. City Performance
![City Performance Bar Chart](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/CITY%20PERFORMANCE%20BAR%20CHART.png)

### C. Booking Breakdown
![Booking Breakdown by Room Type](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/BOOKING%20BREAKDOWN%20BY%20ROOM%20TYPE.png)

![Booking Breakdown by Status](https://raw.githubusercontent.com/wisemansg/hotel_booking_analytics/main/assets/BOOKING%20BREAKDOWN%20BY%20STATUS.png)

## 🛠️ 6. Technology Stack
* **Cloud Platform:** Snowflake
* **Frontend/App:** Streamlit (Python)
* **Data Manipulation:** SQL & Pandas


