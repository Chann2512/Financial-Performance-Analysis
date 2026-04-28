# 📊 Financial Performance Analysis Dashboard

## 📌 Overview
This project analyzes financial performance using a structured P&L dataset to identify profitability drivers, cost inefficiencies, and business risks across multiple business lines.

---

## 🧩 Business Context
A multi-sector company in the Sports & Health industry aims to:
- Maintain sustainable profitability  
- Optimize cost structure (COGS & Opex)  
- Allocate resources efficiently  

The company experienced significant profit volatility, especially a sharp decline in mid-year performance.

---

## ❓ Problem
Profit dropped significantly despite relatively stable cost levels.

Key questions:
- What caused the mid-year profit decline?  
- Which segments are underperforming?  
- Is the company scaling efficiently with revenue?  

---

## 🔍 Analytical Approach

### 1. Data Modeling
- Designed a **star schema**
  - Fact table: 580 financial transactions  
  - Dimension tables: Calendar, Group, Subgroup, KPI, Ratios  
- Structured data to support full P&L analysis (Revenue → Net Profit)

---

### 2. Data Processing (SQL)
- Cleaned and validated raw data  
- Joined fact and dimension tables  
- Aggregated metrics by time, business line, and cost category  
- Calculated key metrics:
  - Revenue, COGS, Opex, Profit  
  - Profit margins and cost ratios  

---

### 3. Analysis Flow

#### Step 1: Trend Analysis
- Analyzed revenue, expense, and profit over time  
- Identified seasonality: Q1 peak → Q3 trough → Q4 recovery  

#### Step 2: Cost vs Revenue Behavior
- Compared revenue decline vs cost reduction  
- Evaluated cost rigidity and operating leverage  

#### Step 3: Business Line Performance
- Compared performance across:
  - Sportswear (main contributor)  
  - Equipment (declining trend)  
  - Nutrition (low efficiency)  

#### Step 4: Cost Structure Deep Dive
- Analyzed:
  - COGS: Labor, Materials, Shipping  
  - Opex: Marketing, Payroll, R&D  
- Identified key cost drivers impacting profit  

#### Step 5: KPI & Efficiency Analysis
- Evaluated:
  - Opex ratio  
  - Gross & Net margins  
  - ROI on Marketing, R&D, Payroll  

---

## 📊 Key Insights
- Profit dropped **87%** due to revenue decline and cost rigidity  
- Costs remained largely fixed despite falling revenue  
- Nutrition segment showed **low ROI and inefficient spending**  
- Revenue highly concentrated in Sales (~80%) → concentration risk  
- Q4 recovery shows strong **operating leverage potential**  

---

## 💡 Recommendations
- Reallocate resources from low-ROI segments (Nutrition)  
- Optimize Opex (Marketing, Payroll)  
- Improve cost flexibility to scale with revenue  
- Diversify revenue streams to reduce dependency  

---

## 📈 Result
Identified key drivers behind an 87% profit decline and proposed strategies to improve margin potential from **8% to 30%+**.

---

## 🛠 Tools & Skills
- SQL (data cleaning, transformation, aggregation)  
- Data Modeling (Star Schema)  
- Power BI (dashboard & visualization)  
- Financial Analysis (P&L, margins, cost structure)

---

## 📷 Dashboard Preview

![Dashboard](https://github.com/user-attachments/assets/e48deb89-c895-44d9-8c5f-50ee4deda29e)

---

## 🔗 Live Dashboard

👉 [View on Power BI](https://app.powerbi.com/view?r=eyJrIjoiNGY4N2U0YWUtZmE0Yy00NWZjLTlkYTItMDQyODY2MTMzMjZlIiwidCI6ImJlODMyOWE3LTcyMTgtNDlhMy05YWMxLWQ3Yjk1NDU2M2YzOSIsImMiOjEwfQ%3D%3D)
