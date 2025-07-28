# 💳 Credit Card Transaction Report Dashboard (Power BI + PostgreSQL)

**Project Objective**

To develop a comprehensive credit card weekly dashboard that provides real-time
insights into key performance metrics and trends,enabling stakeholders to monitor 
and analyze credit card operations effectively.

---

## 📊 Overview

The dashboard provides clear, actionable visualizations of customer transactions, trends, volume patterns, and weekly metrics. It supports business intelligence analysis for financial decision-making and monitoring transaction activity over time.

---

**Project Insights- Week 53 (31st Dec)**

**WoW change:**
- Revenue increased by 28.8%

**Overview YTD:**
- Overall revenue is 57M
- Total interest is 8M
- Total transaction amount is 46M
- Male customers are contributing more in revenue 31M, female 26M
- Blue & Silver credit card are contributing to 93% of overall transactions
- TX, NY & CA is contributing to 68%
- Overall Activation rate is 57.5%
- Overall Delinquent rate is 6.06%]

---

## ✅ Features

- Dynamic weekly data updates via PostgreSQL connection
- Auto-refreshing Power BI dashboard
- Key metrics: Transaction Volume, Count, Customer Segments
- Trend analysis and filtering by week/date range
- Visual KPIs with drill-down capability

---

## 🗃️ Data Source

- **Database:** PostgreSQL (accessed via pgAdmin 4)
- **Tables:** Weekly appended transaction data
- **Refresh Method:** DirectQuery / Scheduled Refresh in Power BI

---

## ⚙️ How it Works

1. PostgreSQL is used to store weekly credit card transaction data.
2. Power BI connects to this database.
3. Whenever new week data is added to the database:
   - Just refresh the report in Power BI.
   - The new data is automatically fetched and visualized.
4. The `.pbix` file contains all the queries, transformations, and visual logic.

---

## 🖼️ Dashboard Preview

![Customer_Dashboard_Screenshot] <img width="661" height="370" alt="Credit_Card_Customer_Dashboard" src="https://github.com/user-attachments/assets/5847217d-2414-4012-943a-1c3659c3757d" />


![Transaction_Dashboard_Screenshot]<img width="672" height="377" alt="Credit_Card_Transaction_Dashboard" src="https://github.com/user-attachments/assets/e6c87060-756c-4079-a0ea-29b6aebb188b" />

---

## 🚀 How to Use

1. Clone this repository or download the `.pbix` file.
2. Ensure you have Power BI Desktop installed.
3. Open the `.pbix` file in Power BI Desktop.
4. Update the data source credentials to point to your local PostgreSQL database (if replicating).
5. Refresh the report.

---

## 🧰 Tech Stack

- 🐘 PostgreSQL (via pgAdmin 4)
- 📊 Power BI Desktop
- 💻 SQL for backend queries
- 🔁 Power BI Refresh Logic

---

## 📂 Files Included

- `Credit_Card_Transaction_Report.pbix` - Main Power BI file
- `README.md` - Project documentation

---

## 📌 Notes

- Make sure PostgreSQL is running and your data is loaded for a full demo.
- This is a sample BI dashboard — sensitive data should be anonymized before sharing publicly.













