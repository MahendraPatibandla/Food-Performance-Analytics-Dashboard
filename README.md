# Food Delivery Performance Analytics Dashboard (Power BI)

An end-to-end Power BI dashboard analyzing food delivery platform performance — covering revenue, customer behavior, restaurant/cuisine trends, and delivery operations — built to surface actionable insights for business and operations teams.

## 📊 Overview

This project consolidates order, customer, restaurant, and delivery data into a single interactive Power BI report with five linked views:

- **Revenue Overview** – total revenue, orders, AOV, and revenue trends by city
- **Customer Analytics** – new vs. repeat customers, revenue by customer type, signup trends
- **Restaurant & Cuisine Performance** – top restaurants by revenue, ratings by cuisine, cost-bucket segmentation
- **Delivery Operations** – on-time vs. late delivery, cancellations by city, delivery time trends
- **Restaurant Drill-Through** – restaurant-level scorecard (revenue, orders, ratings, delivery status) accessible from the main report

## 🔑 Key Metrics Tracked

| Metric | Value |
|---|---|
| Total Revenue | ₹165M |
| Total Orders | 200K |
| Avg Order Value | ₹824.57 |
| Avg Delivery Time | 44.55 min |
| On-Time Delivery Rate | 51.88% |
| Repeat Customer Rate | 50.28% |
| Total Restaurants | 56K |

## 💡 Key Insights

- Identified a **48% late-delivery rate**, with cancellations concentrated in a small number of cities — pointing to specific logistics bottlenecks rather than a system-wide issue.
- Found nearly an even **50/50 split between new and repeat customers**, with repeat customers contributing a disproportionate share of revenue.
- Segmented orders by cost bucket, showing **Budget-tier orders make up ~59%** of volume while Premium and Mid-Range drive a higher share of revenue per order.
- Built a **restaurant drill-through view** so any restaurant's revenue, delivery performance, and customer mix can be reviewed individually without leaving the report.

## 🛠️ Tools & Techniques

- **Power BI Desktop** – report design and data modeling
- **DAX** – calculated measures (AOV, repeat customer %, on-time %, revenue per restaurant)
- **Power Query** – data cleaning and transformation
- **Interactive filtering & drill-through** – city-wise filters, cuisine/cost segmentation, restaurant-level drill-through pages

## 📁 Repository Contents

- `Food_Delivery_Dashboard.pdf` – exported dashboard screenshots
- (add your dataset source/link here if public)

## 🚀 How to Use

1. Clone this repository
2. Open `Food_Delivery_Dashboard.pbix` in Power BI Desktop
3. Use the city, cost-bucket, and cuisine filters to explore the data
4. Click into any restaurant on the Revenue by City table to open the drill-through scorecard

## 📌 Notes

This project was built using a food delivery dataset for analytical/portfolio purposes and is not affiliated with or sourced from any specific commercial platform.

---
**Author:** Patibandla Mahendra
[LinkedIn](#) | [GitHub](#)
