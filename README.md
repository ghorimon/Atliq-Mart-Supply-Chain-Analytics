# 🚀 Supply Chain Dashboard – FMCG Domain  
*From raw transactions to strategic insights*

---

## 🎯 Project Summary  
As a data-driven professional specialising in the **FMCG and supply-chain domain**, I built this Power BI dashboard to transform complex, high-volume transaction data into **decision-ready visualisations**.  
The goal: help stakeholders see what truly matters — and act on it.

---

## 🧩 Problem Statement  
- The company’s supply chain faced challenges: stock-outs, late deliveries, and poor visibility across regions.  
- Business users wanted to know:  
  *“Where are we losing margin? What’s causing delays? Which regions or products drag down OTIF (On-Time & In-Full)?”*  
- The mission: **build a Power BI dashboard** that surfaces these answers, reveals bottlenecks, and enables proactive strategy.

---

## 🧩 Data Model  <img src="Dashboard_View/Data_Model.png" alt="Data Model" width="200" align="right" />

**Tables Used:**

- **fact_orders** → Order-level details (Order ID, Product, Qty, Dates, Delivered Qty)  
- **fact_orders_summary** → Aggregated order metrics including OT%, IF%, OTIF%  
- **dim_customers** → Customer info (Customer ID, Name, City, Segment)  
- **dim_products** → Product info (Product ID, Name, Category, Brand)  
- **dim_date** → Calendar table (Day, Week, Month, Quarter, Year)  
- **dim_targets** → SLA and performance targets for each region or partner  

📘 *The model follows a Star Schema — with fact tables linked to multiple dimension tables for efficient reporting.*

---

## 🔍 What I Built  

| Section | Description |
|----------|-------------|
| **Overview** | High-level KPIs covering total volume, value, OT, IF, and OTIF with trend insights. |
| **Region & Channel** | Regional and sales-channel performance views to identify strong/weak zones. |
| **Product & Category** | Focus on top SKUs, margin drivers, slow movers, and returns. |
| **Delivery Analytics** | Deep dive into delivery delays, reasons, and partner performance. |
| **Recommendations** | Clear, actionable takeaways — e.g., prioritise replenishment for Category X in Region Y. |

---

## 🛠️ Tools & Techniques  
- **Power BI Desktop** – Data modelling (star schema), DAX measures, interactive visuals.  
- **ETL & Pre-Processing** – Power Query M and Excel for data cleaning and transformation of 300 K+ transactions.  
- **Data Model** – Fact (Transactions) + Dimensions (Product, Region, Date, Logistics Partner).  
- **KPI Focus** – OT%, IF%, OTIF%, Avg Delay (days), Margin % by SKU.  
- **Storytelling** – Designed for business clarity; minimal jargon, maximum insight.

---

## 📊 Key Insights Delivered  
- **~42% OTIF** overall → over half the orders are delayed or incomplete.  
- **Region A** leads in OT but lags in IF — supply reliability varies.  
- **Category C** shows highest margin drop but fastest growth → optimisation opportunity.  
- Orders delayed by **1–3 days = 68%** of all late orders → logistics review needed.  
- **15 SKUs** caused **47% of lost value** due to stock-outs.

---

## ✅ Recommendations  
1. **Reset OTIF target** to 60% within 6 months, with monthly regional checkpoints.  
2. **Logistics review** – renegotiate SLA terms with Partner X; Region B avg delay = 2.4 days.  
3. **Inventory prioritisation** – focus on top 15 SKUs with margin loss; pre-position stock in Region C.  
4. **Channel strategy** – Channel Z’s rapid growth demands real-time fulfilment alerts.  
5. **Dashboard rollout** – share via Power BI Service, review insights monthly.

---

## 📁 How to Use This Repo  
1. Clone or download the Power BI `.pbix` file from this repo.  
2. Ensure the dataset structure matches (`data/` folder).  
3. Open in **Power BI Desktop** → explore via filters (Region, Product, Time).  
4. Customise visuals, colours, or metrics to fit your needs.

---

## 📖 Learnings & Next Steps  
- Leveraged **DAX time-intelligence** (`SAMEPERIODLASTYEAR`, `DATEADD`) for trend analysis.  
- Understood how critical **data cleaning** is for accuracy (delays, duplicates, partner tags).  
- Next phase: integrate **live refresh in Power BI Service**, add **forecasting** and **mobile layout**.

---

## 🌐 Connect & Explore  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/rimonghosh/)  
[![Portfolio](https://img.shields.io/badge/NovyPro-Portfolio-orange)](https://www.novypro.com/project/supply-chain-analytics---fmcg-domain)

---

⭐ **If you liked this project**, consider giving it a star — it motivates me to build more insightful dashboards!  
