# 🛍️ Retail KPI Advanced Analysis

> End-to-end retail analytics project covering KPI modeling, dashboard development, and strategic scenario simulation.

---

## 📌 Project Overview

This project demonstrates advanced retail performance analysis using transaction-level data. It combines:

* Data cleaning & transformation
* KPI framework design
* Power BI dashboard development
* Conversion & pricing scenario simulations
* Executive-level business insights

The objective is to simulate how a modern retail analytics team would evaluate revenue, profitability, marketing efficiency, and customer performance.

---

## 🗂 Project Structure

```
Retail-KPI-Advanced-Analysis/
│
├── data/
│   ├── raw_retail_data.csv
│   ├── cleaned_retail_data.csv
│   └── data_dictionary.md
│
├── dashboard/
│   ├── retail_kpi_dashboard.pbix
│   ├── dashboard_mockup.png
│   └── measures_documentation.md
│
├── scenario/
│   ├── conversion_simulation.xlsx
│   ├── pricing_sensitivity_model.xlsx
│   └── scenario_assumptions.md
│
├── insights.pdf
└── README.md
```

---

## 📊 Dataset Description

The dataset contains transaction-level retail data.

### 🔹 Core Fields

* Order_ID
* Order_Date
* Customer_ID
* Region
* Channel (Online / In-Store)
* Product_Category
* Product_Subcategory
* Units_Sold
* Unit_Price
* Discount (%)
* Revenue
* Cost
* Profit
* Marketing_Spend
* Conversion_Rate
* Customer_Segment

### 🔹 Derived Metrics (Data Modeling Layer)

* **Net Revenue** = Units_Sold × Unit_Price × (1 - Discount)
* **Gross Profit** = Net Revenue - Cost
* **Profit Margin %**
* **Average Order Value (AOV)**
* **Customer Lifetime Value (CLV - proxy model)**

Cleaned dataset available in:

```
data/cleaned_retail_data.csv
```

---

## 📈 KPI Framework

### 1️⃣ Revenue KPIs

* Total Revenue
* Revenue Growth % (MoM / YoY)
* Revenue by Region
* Revenue by Channel
* Revenue by Category

### 2️⃣ Profitability KPIs

* Gross Profit
* Net Profit
* Profit Margin %
* Contribution Margin

### 3️⃣ Sales & Conversion KPIs

* Conversion Rate
* Units per Transaction
* Average Order Value (AOV)
* Incremental Revenue from Conversion Uplift

### 4️⃣ Marketing Efficiency KPIs

* Marketing Spend
* Revenue per Marketing Dollar
* Customer Acquisition Cost (Estimated)
* Return on Marketing Investment (ROMI)

### 5️⃣ Customer KPIs

* Active Customers
* Repeat Purchase Rate
* Revenue by Segment
* Estimated CLV

---

## 📊 Power BI Dashboard

File:

```
dashboard/retail_kpi_dashboard.pbix
```

### Dashboard Pages

### 🔹 Executive Overview

* KPI Cards (Revenue, Profit, Margin, Conversion)
* Monthly revenue trend
* Regional performance breakdown

### 🔹 Sales Performance

* Category & subcategory contribution
* Channel comparison (Online vs In-Store)
* Discount impact on margin

### 🔹 Customer Analytics

* Segment performance
* AOV by segment
* Repeat vs New customer behavior

### 🔹 Marketing Performance

* Marketing Spend vs Revenue
* ROMI trend
* Conversion rate analysis

---

## 🧮 Scenario Modeling

### 📌 1. Conversion Simulation

File:

```
scenario/conversion_simulation.xlsx
```

**Purpose:**
Simulate the financial impact of improving conversion rate.

**Inputs:**

* Website Traffic
* Baseline Conversion Rate
* Improved Conversion Rate (+1%, +2%, +5%)
* Average Order Value
* Profit Margin

**Core Logic:**

```
Orders = Traffic × Conversion Rate
Revenue = Orders × AOV
Profit = Revenue × Profit Margin
```

**Outputs:**

* Incremental Orders
* Incremental Revenue
* Incremental Profit
* % Revenue Uplift

---

### 📌 2. Pricing Sensitivity Model

File:

```
scenario/pricing_sensitivity_model.xlsx
```

Evaluates the impact of:

* ±5% Price Changes
* Discount Adjustments
* Volume Elasticity Assumptions

Scenarios included:

* Base Case
* Price Increase
* Price Decrease
* High Discount Campaign

---

## 📄 Key Insights (Executive Summary)

* Online channel is the primary revenue growth driver.
* High discounting increases revenue but significantly compresses margins.
* A small improvement in conversion rate creates strong profit leverage.
* Marketing efficiency varies by region and segment.
* High-volume categories are not always high-margin categories.

Full report available in:

```
insights.pdf
```

---

## 🛠 Tools & Skills Demonstrated

* Data Cleaning & Transformation
* KPI Framework Design
* Power BI Dashboard Development
* DAX Measures & Data Modeling
* Scenario & Financial Simulation
* Business Insight Generation

---

## 🚀 How to Use

1. Open `cleaned_retail_data.csv` to explore the dataset
2. Launch the Power BI dashboard file
3. Test strategic decisions using scenario Excel models
4. Review insights.pdf for executive-level summary

---

## 💼 Resume-Ready Project Description

**Retail KPI Advanced Analytics Project**
Designed and built an end-to-end retail analytics solution including KPI modeling, Power BI dashboard development, and financial scenario simulations. Analyzed revenue drivers, marketing efficiency, pricing sensitivity, and conversion optimization to deliver strategic business recommendations.

