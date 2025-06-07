# 🏍️ Motorcycle Parts Sales Report Project

## Table of Contents

* [Project Overview](#project-overview)
* [Data Source](#data-source)
* [Tools Used](#tools-used)
* [Data Cleaning/Preparation](#data-cleaningpreparation)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Data Analysis](#data-analysis)
* [Results/Findings](#resultsfindings)
* [Recommendations](#recommendations)
* [Limitations](#limitations)

---

## Project Overview

This project presents a sales performance report for a company that sells motorcycle parts through three warehouses. It uses Excel to analyze and visualize data from June to August 2021, uncovering insights into payment behavior, product line performance, warehouse contributions, and client type trends.

---

## Data Source

The dataset contains daily sales transactions from three warehouses:
- **Fields include**: `date`, `warehouse`, `client_type`, `product_line`, `quantity`, `unit_price`, `total`, and `payment method`.
- The dataset spans from **June to August 2021**.

---

## Tools Used

* **Microsoft Excel** – for data organization, pivot table analysis, and dashboard creation.

---

## Data Cleaning/Preparation

- ✅ The dataset was **already clean** — no missing values or structural issues.
- Therefore, **no transformations** or corrections were required.

---

## Exploratory Data Analysis

Key questions explored in this analysis include:

1. What is the total sales distribution across payment methods?
2. What is the average unit price per product line?
3. How do warehouses compare in total sales?
4. What’s the average transaction size by client type (retail vs wholesale)?
5. How do monthly sales trends vary over the three months?
6. Which product lines generate the most quantity sold?
7. Which product lines dominate in each warehouse?

---

## Data Analysis

All analysis was conducted using **Pivot Tables** and **Pivot Charts** in Excel. Key features include:

- KPI Cards for:
  - Total Sales
  - Total Quantity Sold
  - Average Unit Price
  - Average Purchase Value
- Visuals used:
  - Pie/Donut Chart: Payment methods
  - Bar Charts: Product line metrics
  - Line Chart: Monthly trend
  - Stacked Bar: Warehouse performance breakdown
- Slicers used for dynamic filtering by:
  - Warehouse
  - Product Line
  - Payment Method
  - Month
  - Client Type

---

## Results/Findings

- **Top Payment Method**: Credit card transactions dominated total sales.
- **Most Expensive Product Line**: Suspension & Traction had the highest average unit price.
- **Best-Performing Warehouse**: The North warehouse led in total sales volume.
- **Client Behavior**:
  - Retail clients had smaller, more frequent transactions.
  - Wholesale clients averaged higher transaction values.
- **Product Line Insights**:
  - Engine and Frame & Body were high-revenue lines.
  - Braking system had high volume but lower revenue per unit.
- **Seasonality**:
  - Sales peaked in July across most product lines.
- **Interactivity**:
  - Slicers allow filtering the dashboard by key fields for custom insights.

---

### Power BI Visuals

To provide a more comprehensive understanding of the data, here are the Power BI visualizations used in this analysis:

#### Employee Overview Page
Provides an overview of the workforce distribution, including gender, location, and racial composition.
<img width="758" alt="image" src="https://github.com/user-attachments/assets/09da992d-0adc-4c1f-9093-a2c2e8285421" />


#### Department and Age Breakdown Page
Focuses on department-level analysis, including gender distribution by department, age group breakdown, and termination rates.
<img width="750" alt="image" src="https://github.com/user-attachments/assets/a18a410e-af65-41c6-9c12-94fe9c5a6178" />


## Recommendations

Based on these findings, the following actions are recommended:

- 💳 **Promote credit card use**: Since it's the most used payment method, consider offering promotions tied to credit card payments.
- 🛠️ **Invest in top-performing lines**: Expand inventory or marketing for Engine and Suspension categories.
- 🧾 **Segment clients for upsell**: Create pricing strategies that better serve high-volume wholesale buyers.
- 📦 **Warehouse optimization**: Analyze operations in the North warehouse to replicate success elsewhere.
- 📈 **Seasonal strategy**: Align marketing campaigns with July demand spikes.

---

## Limitations

- Data only spans **three months** — trends may not reflect long-term patterns.
- **Client identities** are not included, so customer-level behavior can’t be tracked.
- No product-level granularity beyond category (`product_line`), which limits deep pricing or SKU analysis.

---
