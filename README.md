Dashboard: https://us-east-1.online.tableau.com/t/robertosepulvedasantos-aba5ea92e0/views/mkt_asigment/Resume


📊 Marketing Mix & Campaign Performance Dashboard
🔎 Project Overview

This project demonstrates an end-to-end marketing analytics workflow:

Data cleaning and table restructuring in SQL

Unification of multi-channel campaign data

Marketing mix calculation using window functions

Performance KPI development (CTR, CPC, Conversions)

Executive dashboard built in Tableau

The objective was to transform raw marketing data into actionable business insights.

🛠 Tech Stack

SQL (CTEs, Window Functions)

Tableau

CSV Data Processing

GitHub Version Control

🗂 Data Processing Steps

Renamed and recreated tables with correct column headers.

Standardized spend columns across all marketing platforms.

Unified 3 separate channel tables using UNION ALL.

Aggregated daily performance by channel.

Calculated marketing mix using:

SUM(total_spend) 
/ SUM(total_spend) OVER (PARTITION BY date)

Exported final dataset to CSV for Tableau visualization.

📈 Key Metrics Created

Total Spend

Total Clicks

Total Conversions

CTR (Click-Through Rate)

CPC (Cost Per Click)

Cost per Conversion

Spend Mix % (Marketing Allocation Share)

📊 Dashboard Features

KPI Summary Cards

Spend Trend by Channel

Marketing Mix Area Chart

Campaign Performance Scatter Plot (CTR vs CPC)

Conversion Efficiency Analysis

Interactive Filters (Date & Channel)

🎯 Business Insights

Identified high-performing campaigns (High CTR, Low CPC)

Measured budget allocation efficiency across channels

Highlighted cost-inefficient campaigns

Provided reallocation recommendations

🧠 What This Project Demonstrates

Advanced SQL window functions

Data modeling & transformation

Analytical KPI design

BI dashboard structuring

Marketing performance optimization logic

📁 Files Included

SQL scripts (table creation + transformation)

Final unified dataset (CSV)

Tableau workbook file

Documentation

🚀 Future Improvements

Add ROAS analysis

Add rolling 7-day metrics

Automate pipeline via Snowflake/DBT

Deploy dashboard to Tableau Public

💼 How To Describe This On LinkedIn

You could post:

Built an end-to-end Marketing Mix & Campaign Performance Analytics project using SQL and Tableau.
Implemented window functions to calculate daily marketing mix allocation and developed KPI dashboards to identify high-performing campaigns and cost inefficiencies.

🎯 Why This Looks Strong

This project shows:

✔ Data engineering
✔ Analytics engineering
✔ Business thinking
✔ BI visualization
✔ KPI design
✔ Optimization mindset
