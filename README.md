# 🍟 Advanced Power BI Project – Crunchy Corner QSR Sales Analysis

This repository contains an end-to-end **Power BI project** analyzing the sales performance of **Crunchy Corner**, 
a major Indian **Quick Service Restaurant (QSR)** chain with over 1000 outlets across India.


---

## 📊 Project Overview

This advanced dashboard project adopts a **consulting mindset**, simulating a real-world business scenario.
It emphasizes **data-driven decision-making** by combining **financial KPIs, category analysis, 
SKU turnover, and cost efficiency**.

- 🧾 Dataset: 2,00,000+ records
- 📌 Focus: Net Revenue, Profitability, Category Mix, SKU Turnover, PVM Analysis,Pareto Analysis
- 📈 Outcome: Strategic insights for sales optimization and margin improvement

---

## 🧾 Data Sources

- Sales transactions (actual & budgeted)
- Product metadata
- Cluster head mapping
- Channel, location & date hierarchies

---

## 🧹 Data Preparation

- Performed via **Power Query**
- Transformed raw data into:
  - ✅ **Fact Table**: Sales & budget metrics
  - ✅ **Dimension Tables**: Product, Cluster Head, Channel, Location, Date

---

## 📐 Data Modeling

- **Star schema** with clear relationships between fact and dimension tables
- Ensures accurate drill-down and filter context in all visuals

---

## 📈 Key Metrics

| Metric                        | Value        |
|------------------------------|--------------|
| Net Revenue                  | $560M         |
| Year-on-Year Growth          | +24.55%       |
| Total SKUs Sold              | 477.87K       |
| Unique SKUs Sold             | 4,207         |
| Gross Profit                 | $162.5M       |
| Net Profit                   | $61.13M       |
| 5-Year Avg SKU Sold          | 956K/year     |

> ⚠️ Note: 2 of the last 5 years showed negative revenue growth,
>  yet the latest YoY growth is strong (+24.55%).

---

## 🧠 Strategic Insights
    - Total Unique SKU  - 4207 
    - 556 SKU gives 80% Revenue
    - 1462 SKU gives 95% Revenue
### 🔍 Category Performance
- Top 3 categories contribute **65% of total revenue**:
  - 🥇 Protein Pack – 39.52%
  - 🥈 Fresh Fare – 14.58%
  - 🥉 Country Fries – 13.66%

### 📦 SKU Turnover Analysis
| Product         | Units Sold % | Revenue %  |
|-----------------|--------------|------------|
| Protein Pack    | 36%          | 39.62%     |
| Fresh Fare      | 7.13%        | 14.58%     |
| Country Fries   | 2.7%         | 13.66%     |
| Cake            | 15.47%       | 4.5%       |
| Frosty Veggies  | 1.49%        | 5.65%      |
| Frosty Fare     | 5.14%        | 4.13%      |

> 🎯 **Low-volume, high-revenue** categories (like Frosty Veggies) offer opportunities for scale.

---

## 🗺️ Regional Insights

- **Uttar Pradesh** consistently contributes ~**34.5–35%** of total net revenue across 8 states.
- ⚠️ Costs are rising:
  - **Raw material costs** have increased every year for the past 4 years
  - **Marketing spend** accounts for ~50% of expenses in UP alone

---

## 👥 Cluster Head Performance

| Cluster Head | Product Sold % | Gross Profit % | YoY Revenue Growth |
|--------------|----------------|----------------|--------------------|
| Dhiraj       | 1.5%           | 37.65%         | 🔼 30.6% (Highest) |
| Umar         | 30%            | 41.78%         | 🔼 25.01%          |

> ✅ **Dhiraj’s cluster**, despite selling fewer products, drives high profitability — indicates effective targeting or pricing.

---

## 💰 Cost Analysis

- **Protein Pack** accounts for **41.83% of total expenses** — requires cost control
- Rising material and marketing costs in key states like Uttar Pradesh are impacting profitability
- Stable gross profit over 5 years despite SKU growth signals **margin compression**

---

## 🔄 Price-Volume-Mix (PVM) Analysis

### 5-Year Trend:
- ✅ **Volume ↑ + Price ↓** → Net revenue increased
- ❌ **Price ↑ + Volume ↓** → Net revenue declined

### Focus Areas:
1. **Country Fries, Fresh Fare, Frosty Veggies**:
   - Increase **volume**, keep **price stable/decreasing** to boost net revenue

2. **Cake**:
   - Needs **growth in both price & volume** to improve contribution

3. **Protein Pack**:
   - Despite strong revenue share, **volume declined in 5 years** → Suggest **price reduction** to recover volume and sustain growth

---

## 📊 Visuals Included

- KPI Cards
- Column, Bar & Donut Charts
- Mekko Chart (custom visual)
- Scatter Plots
- Filters & Slicers (Year, Category, Channel, Region)

---

## 🧠 Skills Demonstrated

- Advanced **DAX** (YoY, YTD, dynamic metrics)
- Power Query (ETL and data shaping)
- Data modeling & schema design
- Business-focused storytelling
- PVM & Variance Analysis for real-world decision support

---

## 💼 Real-World Relevance

This project mimics an industry-grade BI solution for:
- QSR, FMCG, Retail, and E-commerce sectors
- Sales and Operations Planning (S&OP)
- Business Analysts, Consultants, and Data Analysts

---

## 📂 Repository Structure
