# Pizza-Sales-Analysis

# 🍕  Pizza Sales Analysis & Power BI Dashboard

A quick, end‑to‑end analytics project that turns raw order data into actionable sales insights for a fictional pizza chain.  
Built to showcase **SQL data modeling, Power BI visualization, and documentation standards**—ideal as a work‑sample or portfolio piece.

---

## 🥅  Project Goals
| # | Objective | Why It Matters |
|---|-----------|----------------|
| 1 | Track revenue, order volume, and average order value (AOV). | Quantify growth and detect downtrends early. |
| 2 | Identify best‑ & worst‑selling pizzas by time period. | Optimize production, marketing, and inventory. |
| 3 | Analyze sales by hour, weekday, and month. | Align labor scheduling and promotions with demand peaks. |
| 4 | Provide an interactive Power BI dashboard. | Enable managers to drill into KPIs without writing queries. |

---

## 📦  Data Source
* **`pizza_sales.csv`** – ~4 000 rows, columns include  
  `order_id`, `order_date`, `pizza_name`, `category`, `quantity`, `total_price`.  
  *(Adapted from the public dataset by @spryguy on Kaggle.)*

---

## 🛠️  Tech & Tools
| Layer | Stack |
|-------|-------|
| **Storage** | Azure SQL Database  |
| **ETL / Modeling** | T‑SQL for staging & star schema, Power Query for minor transforms |
| **Visualization** | Power BI Desktop (.pbix) |
| **Version Control** | Git + GitHub |

---

📈 Dashboard Highlights
KPI cards: Total Revenue, AOV, Total Orders

Stacked bar: Top 5 pizzas vs. revenue

Heat‑map: Orders by weekday × hour

Trend line: Monthly revenue with YOY % change

Slicers: Category, Size, Month, Order Method
