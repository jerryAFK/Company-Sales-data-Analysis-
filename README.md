# 📊 Data Modeling & Business Intelligence Dashboard Project

## 🔍 Project Title: **Revenue Insights Using Dimensional Modeling**

Snapshot: Go to screenshots of the project to view MySQL Workbench screenshots and my handwritten notes of the introduction to the "Demo company" I have taken for this project.

This project presents a complete **Business Intelligence (BI)** pipeline—from raw data to a fully functional dashboard using **dimensional modeling (Star Schema)** and modern BI tools. The dashboard helps visualize business performance, revenue trends, and customer distribution across different dimensions like region, year, and channel.

---

## 🧠 Project Objectives

- Design a scalable **data model** using industry-standard **Star Schema**.
- Perform data cleaning, transformation, and modeling.
- Build an interactive **dashboard** for executives and stakeholders.
- Provide insights into revenue patterns, customer types, and sales channels.


---

## 🧩 Data Modeling (Star Schema)

This project follows a **Star Schema** approach which is best suited for OLAP systems and BI tools. The schema includes:

**Fact Table:**
  - `fact_sales`
  - `DateKey`
  - `ProductKey`
  - `CustomerKey`
  - `ChannelKey`
  - `CountryKey`
  - `Revenue`
  - `Units Sold`

**Dimension Tables:**
- `dim_date` – Date, Month, Year, Quarter  
- `dim_product` – Product ID, Name, Category  
- `dim_customer` – Customer ID, Type, Segment  
- `dim_channel` – Channel Name (Online, In-Store, etc.)  
- `dim_country` – Country, Region, Continent  

📌 *Benefits:*  
- Simplified queries  
- Improved dashboard performance  
- Better scalability and analytical depth


---

## 🖥️ Dashboard Overview

An interactive dashboard is created using **Power BI**, visualizing:

- 📅 **Year-wise Revenue Trends**
- 🌍 **City-level Sales Performance**
- 📈 **Revenue by Customer Type**
- 🛍️ **Channel Distribution**
- 🔄 **YOY Growth Analysis**


The visuals are dynamic and allow users to filter by year, country, and sales channel.

---

## 🧼 Data Preprocessing

Before modeling, the dataset underwent the following preprocessing steps:

- ✅ **Missing Value Handling**  
- 🔄 **Data Type Conversion**  
- 🔍 **Duplicate Removal**  
- 🧠 **Date Formatting and Key Generation**  
- 🔗 **Primary-Foreign Key Relationships Setup**



---

## 🛠️ Tools & Technologies

| Tool/Technology | Purpose |
|-----------------|---------|
| **Power BI / Tableau** | Dashboarding & Visualizations |
| **MS Excel / CSV** | Raw data storage and initial preprocessing |
| **SQL (optional)** | ETL, Joins, Filters |
| **Star Schema** | Data modeling strategy |
| **DAX / Calculated Fields** | Advanced KPI creation |

---

## 📊 Key Insights

- The **majority of revenue** in 2020 came from a few key countries.
- **Online channels** showed the highest growth compared to in-store channels.
- **Enterprise customers** had a significantly higher average order value.
- The **Q4 period** consistently sees a revenue spike across all regions.

---

## 🎯 Outcomes & Impact

- Improved clarity of business performance through visual KPIs.
- Quick filtering and drill-down analysis enabled better decision-making.
- Enhanced reporting structure that can scale across years or geographies.

---
