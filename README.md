# 🚗 BMW Sales Analytics Dashboard

### Sales Performance, Revenue & Profitability Analysis

A professional Tableau dashboard designed to analyze BMW sales performance across different models and regions.

The project focuses on understanding sales volume, revenue, cost, profitability, pricing, regional performance, and model-level performance through interactive visualizations.

---

## 📌 Project Overview

The BMW Sales Analytics project analyzes automobile sales data to identify important business patterns across:

- BMW Models
- Regions
- Units Sold
- Revenue
- Cost
- Profit
- Profit Margin
- Average Price

The dashboard provides multiple analytical views to help understand sales and profitability performance.

---

## 🎯 Business Questions

This project answers the following business questions:

- Which BMW model generates the highest revenue?
- Which BMW model generates the highest profit?
- Which model has the highest profit margin?
- Which region performs best in terms of sales?
- How does revenue vary across regions?
- How does profit vary across models?
- What is the relationship between units sold and profit?
- How are prices distributed across BMW models?
- Which models and regions contribute most to overall performance?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Tableau | Interactive dashboard and data visualization |
| Microsoft Excel | Dataset and data preparation |
| GitHub | Project documentation and portfolio |

---

## 📊 Dataset

The dataset contains BMW sales records with the following fields:

| Column | Description |
|---|---|
| Model | BMW vehicle model |
| Region | Sales region |
| Units Sold | Number of units sold |
| Price | Selling price |
| Cost | Cost per unit |
| Profit | Profit generated |

### Dataset Summary

- **Records:** 200
- **Models:** 6
- **Regions:** 4
- **Models:** BMW X1, BMW X3, BMW X5, BMW 3 Series, BMW 5 Series, BMW 7 Series

---

# 📈 Dashboard Pages

## 1️⃣ Home / Landing Page

The Home page provides an introduction to the dashboard and navigation to different analytical sections.

### Includes:

- BMW Sales Analytics branding
- Dashboard navigation
- Number of models
- Number of regions
- Number of records
- Total units sold
- Total revenue
- Total profit

![Home Dashboard](Screenshots/1.%20Home.png)

---

## 2️⃣ Executive Overview

Provides a high-level summary of overall BMW sales performance.

### KPIs:

- Total Revenue
- Total Units Sold
- Total Profit
- Average Price
- Profit Margin %

### Visualizations:

- Revenue by Model
- Revenue by Region
- Revenue vs Profit Analysis

![Executive Overview](Screenshots/2.%20Overview.png)

---

## 3️⃣ Model Analysis

This page compares the performance of different BMW models.

### Analysis Includes:

- Units Sold by Model
- Revenue by Model
- Profit by Model
- Average Price by Model
- Top Performing Model

![Model Analysis](Screenshots/3.%20Model.png)

---

## 4️⃣ Region Analysis

This dashboard page compares BMW sales performance across four regions.

### Analysis Includes:

- Units Sold by Region
- Revenue by Region
- Profit by Region
- Model × Region Breakdown
- Top Performing Region

![Region Analysis](Screenshots/4.%20Region.png)

---

## 5️⃣ Revenue & Profit Analysis

This page focuses on revenue, cost and profitability.

### Analysis Includes:

- Top Revenue Model
- Total Cost
- Total Profit
- Profit Margin %
- Average Profit per Record
- Revenue vs Profit
- Profit Margin by Model
- Revenue vs Cost
- Profit by Model and Region

![Revenue & Profit](Screenshots/5.%20Revenue%20%26%20Profit.png)

---

## 6️⃣ Time & Distribution Analysis

This page focuses on distribution patterns and the relationship between units sold and profit.

### Analysis Includes:

- Total Records
- Peak Units Sold
- Minimum Units Sold
- Average Units Sold
- Price Distribution
- Units Sold Distribution
- Profit vs Units Sold Scatter Plot

![Time Analysis](Screenshots/6.%20Time%20Analysis.png)

---

## 7️⃣ Quick Analysis

The Quick Analysis page provides interactive metric and dimension selection.

### Metric Selection:

- Revenue
- Profit
- Units Sold
- Average Price
- Profit Margin %

### Dimension Selection:

- Model
- Region
- Price Range
- Unit Range
- Profit Tier

The dashboard dynamically changes based on the selected metric and dimension.

![Quick Analysis](Screenshots/7.%20Quick%20Analysis.png)

---

# 🔑 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | $117.29M |
| Total Cost | $84.41M |
| Total Profit | $32.88M |
| Total Units Sold | 1,974 |
| Average Price | $59,361 |
| Profit Margin | 28.03% |
| Total Records | 200 |

---

# 🚗 Model Performance

| Model | Units Sold | Revenue | Profit | Profit Margin |
|---|---:|---:|---:|---:|
| BMW X3 | 421 | $25.27M | $7.16M | 28.34% |
| BMW X1 | 385 | $22.51M | $6.76M | 30.02% |
| BMW 7 Series | 364 | $22.52M | $6.37M | 28.28% |
| BMW 3 Series | 355 | $21.37M | $5.89M | 27.55% |
| BMW 5 Series | 236 | $13.91M | $3.47M | 24.93% |
| BMW X5 | 213 | $11.71M | $3.24M | 27.64% |

---

# 🌎 Regional Performance

| Region | Units Sold | Revenue | Profit |
|---|---:|---:|---:|
| North | 560 | $33.76M | $9.00M |
| West | 482 | $30.49M | $8.33M |
| South | 474 | $27.57M | $8.07M |
| East | 458 | $25.46M | $7.48M |

---

# 🧮 Calculated Metrics

The dashboard uses calculated metrics such as:

### Revenue

```text
Revenue = Price × Units Sold
