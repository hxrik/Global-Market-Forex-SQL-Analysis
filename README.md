# Global-Market-Forex-SQL-Analysis
Snowflake + Power BI project for market and macroeconomic analysis: NIFTY, S&amp;P500, FTSE100, USD-INR and country-level GDP, inflation, interest rates, and exchange rates.

# 🌍 Global Market & Forex Analysis (Snowflake + Power BI)

## 📌 Project Overview
This project analyzes **global forex and market performance** using **Snowflake SQL** for data transformation, analytics, and correlation studies, and **Power BI** for rich visual exploration.

Markets covered:
- **NIFTY**
- **S&P 500**
- **FTSE 100**
- **USD–INR Exchange Rate**

Economic indicators analyzed separately:
- **Inflation**
- **GDP Growth**
- **Lending Interest Rates**
- **Exchange Rates**

> ❗ Note: Forex and economic indicators are **not merged for insights** due to non-overlapping behavior and different time granularities in the datasets.

---

## 🛠️ Tech Stack
- **Snowflake** – Data Warehousing, Cleaning, Transformations, Correlations
- **SQL** – Feature Engineering, Market Joins, Trend & Relationship Analysis
- **Power BI** – Interactive Dashboards (Forex + Economic Insights)
- **GitHub** – Version Control & Documentation

---

## ✅ What Was Done

### 🔹 1. Snowflake Data Engineering
✔ Built warehouse, schemas, and staging  
✔ Unpivoted and cleaned 50+ years of macroeconomic data  
✔ Standardized Forex market data into unified `MARKET_FINAL` table  
✔ Created analytical views and correlation tables  
✔ Engineered ML-ready dataset (stored for future use, **not modeled here**)  

---

### 🔹 2. Forex Market Analysis (Power BI)
✔ Price trend comparisons across 4 markets  
✔ Moving average, % change, and volume behavior  
✔ Market-to-market correlation insights  
✔ Volatility and daily movement patterns  

---

### 🔹 3. Economic Indicators Dashboard
✔ Inflation trends by country (YoY and rankings)  
✔ GDP growth and lending interest behavior  
✔ Geographic inflation mapping  
✔ KPI indicators and trend direction visuals  

---

## 💡 Key Insights
- **Global markets show directional similarity during high volatility periods**, especially NIFTY and S&P 500.
- **Forex (USD-INR) movement does not align proportionally with equity index movement**, showing independent trend behavior.
- **Inflation spikes are country-specific rather than global synchronized jumps**, indicating localized economic pressure.
- **Market volume anomalies often appear before major price shifts**, especially in NIFTY.
- **Different markets require separate analytical approaches**, hence separate dashboards were created for Forex and Economic trends.

---

## 🗂 Files Included
| File | Purpose |
|------|---------|
| `main.sql` | Data ingestion, cleaning, warehouse setup |
| `analysis.sql` | Correlation studies, views, ML feature table creation |
| `Economic_Dashboard.pbix` | Power BI dashboards (Forex + Economics) |
| `Raw Data Referenced.md` | Original data sources |

---

## 📌 Notes
- The table `FOREX.ML_MARKET_FEATURES` is generated in `analysis.sql` and stored for **future modeling use**.
- No ML modeling is performed in this project.

---

### 🚀 Build Summary
> **Snowflake for backend analytics → Power BI for storytelling → SQL for insight generation**
