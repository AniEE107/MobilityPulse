# 🚗 MobilityPulse – Ride & Cancellation Analytics Dashboard

**MobilityPulse** is an interactive **Power BI dashboard** that provides deep insights into ride-sharing operations, cancellations, revenue, and user behavior. The goal is to help mobility companies monitor performance, identify operational bottlenecks, and improve the rider experience.

---

## 📊 Key Features

- ✅ **Total Rides, Revenue, and Active Users**
- 📉 **Cancellation Rate by Reason** (e.g., driver unavailability, customer no-show)
- 📅 **Daily/Weekly Ride Trends** to spot usage patterns
- 🗺️ **Zone/City-Level Heatmaps** of ride demand
- ⏱️ **Idle Time & Utilization KPIs** for fleet optimization
- 💸 **Customer Spend & Ride Frequency Analysis**

---

## 🛠️ Tools & Tech

| Tool/Tech      | Purpose                            |
|----------------|------------------------------------|
| **Power BI**   | Visualization & dashboarding       |
| **Power Query**| Data cleaning & transformation     |
| **DAX**        | Calculated measures and KPIs       |
| **Excel/CSV**  | Data source (ride logs, user info) |

---

## 📁 Dataset Structure

The dashboard is built on cleaned, preprocessed data including:

- `rides.csv`: ride_id, customer_id, vehicle_id, start_time, end_time, fare
- `cancellations.csv`: reason, timestamp, driver_id, ride_id
- `zones.csv`: location_name, lat/lon, region
- `users.csv`: registration date, rating, total rides

---

## 📷 Dashboard Preview

Here are snapshots of the dashboard in action:

### 1. Ride Trends Overview
![Ride Trends](https://raw.githubusercontent.com/AniEE107/MobilityPulse/main/ola_1.png)

### 2. Cancellations Breakdown
![Cancellations](https://raw.githubusercontent.com/AniEE107/MobilityPulse/main/ola_2.png)

### 3. Regional Demand & Fleet Utilization
![Utilization](https://raw.githubusercontent.com/AniEE107/MobilityPulse/main/ola_3.png)

### 4. Revenue and Profitability Insights
![Revenue](https://raw.githubusercontent.com/AniEE107/MobilityPulse/main/ola_4.png)

### 5. Rider Behavior & Loyalty Metrics
![User Analysis](https://raw.githubusercontent.com/AniEE107/MobilityPulse/main/ola_5.png)

> 📌 The dashboard allows interactive filtering by city, time, and ride status.

---

## 🔍 Use Case Scenarios

- 🚩 Spot high-cancellation zones to adjust fleet allocation
- 🕒 Identify peak ride hours for dynamic pricing
- 🔁 Track repeat riders and loyalty indicators
- 📉 Detect zones with high idle time or low driver utilization

---

## 🧠 Key Insights

- 40% of cancellations came from just 3 zones during peak hours  
- Average fleet utilization dropped below 60% during weekends  
- Top 10% users contributed over 50% of revenue

---

## 🚀 Possible Enhancements

- Real-time refresh from live APIs
- Forecasting ride demand using time series models
- Drillthrough reports for individual driver/rider performance
- Integration with IoT/telematics data for fleet monitoring

---

## 👨‍💻 Author

**Manish Kumar**  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile)  
📁 [Portfolio](https://github.com/AniEE107)

---

## 📌 Disclaimer

> This dashboard was created for demonstration purposes using sample or anonymized data.

---
