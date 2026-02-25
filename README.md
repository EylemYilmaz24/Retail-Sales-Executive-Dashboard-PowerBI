# Retail Sales Analysis – Power BI Project

![Executive Dashboard](dashboard-preview.png)

## 📊 Project Overview

This project is a portfolio-level Business Intelligence solution built in Power BI using the Online Retail II dataset.

The objective is to analyze revenue performance, customer behavior, and product dynamics through structured dashboards and business-driven insights.

---

## 📁 Dataset

Online Retail II (UK-based e-commerce transactional dataset)

Includes:

- InvoiceNo  
- InvoiceDate  
- Customer ID  
- Quantity  
- UnitPrice  
- Country  

Clean dataset size: ~1,041,000 rows

---

## 🛠 Data Preparation

- Appended 2009–2010 and 2010–2011 datasets  
- Removed returns (negative quantities)  
- Removed zero / negative unit prices  
- Created calculated column:  
  `Revenue = Quantity × UnitPrice`

---

# 📈 1️⃣ Executive Dashboard

### Key KPIs

- Total Revenue  
- Total Orders (Distinct Invoice Count)  
- Average Order Value (AOV)  

### Visual Analysis

- Monthly Revenue Trend  
- Revenue by Country  
- Executive KPI layout  

This dashboard provides a high-level revenue performance overview suitable for management reporting.

---

# 👥 2️⃣ Customer Analysis

![Customer Analysis](customer-analysis.png)

### Key Insights

- Active customers represent the largest segment.  
- Lost customers still account for a meaningful portion of historical revenue.  
- At-Risk customers indicate reactivation potential and churn risk.  

This page focuses on customer segmentation and behavioral analysis.

---

# 📦 3️⃣ Product Intelligence

![Product Intelligence](product-intelligence.png)

### Key Insights

- Total Products: 4,745  
- Top 20 products generate only **13.9%** of total revenue  
- Revenue is widely distributed across the product portfolio  
- Product segmentation highlights high- and low-performing SKUs  

This analysis reveals a diversified product structure rather than strong revenue concentration in a limited number of products.

---

## 🔎 Skills Demonstrated

- Data cleaning & transformation (Power Query)  
- DAX measures and calculated columns  
- KPI design and executive layout  
- Revenue concentration (Pareto) analysis  
- Customer and product segmentation  

---

## 🛠 Tools Used

- Power BI  
- DAX  
- Power Query  
