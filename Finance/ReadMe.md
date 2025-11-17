# Finance Analytics Dashboard

This Looker dashboard provides a comprehensive financial analysis across sales, profit, cost, pricing, promotions, and product performance. Looker’s semantic model and interactive dashboard filters allow users to explore financial KPIs, analyze trends, and drill into country-level and product-level profitability.

---

## 📌 Overview

The dashboard presents a unified financial view with the following top-level metrics:

- **Total Sales:** 55.4M  
- **Total Profit:** 31.6M  
- **Sales Cost:** 23.8M  
- **Unit Cost:** 1.9M  
- **Price:** 4.4M  
- **Products:** 1.6K  

These values are generated using Looker’s aggregated metrics via the underlying explore.

A **Region filter** allows users to segment financial insights geographically.

---

## 📊 Dashboard Sections & Insights

### **1. KPI Tiles**
The top tiles use Looker’s *single value visualizations* to summarize:
- Sales  
- Profit  
- Sales Cost  
- Unit Cost  
- Price  
- Product Count  

These metrics adjust dynamically based on selected filters.

---

### **2. Profit by Country**
A horizontal bar chart showing profit distribution across multiple countries.  
Users can:
- Compare country performance  
- Drill into specific regions  
- Understand geographic profitability spread  

---

### **3. Profit by Product Category**
Displays profit split across categories such as:
- Computers  
- Cameras & Camcorders  
- TV & Video  
- Cell Phones  
- Audio  

Useful for strategic product analysis.

---

### **4. Profit by Product Sub-Category**
Breaks down category performance into more specific subcategories (e.g., laptops, smartphones, projectors).  
This helps identify the most profitable product groups at a granular level.

---

### **5. Promotion-Level Profitability**
Shows revenue and profitability by promotional campaign, including:
- Holiday promotions  
- Seasonal promotions  
- Back-to-school promotions  
- Region-specific campaigns  
- No-discount scenarios  

Helps evaluate promotion effectiveness.

---

### **6. Sales & Profit – Monthly Trend**
A combined bar + line chart visualizing:
- Monthly profit (bars)  
- Monthly sales (line)  

Reveals:
- Seasonality in demand  
- Profit–sales alignment  
- Month-over-month fluctuations  

---

### **7. Quarterly Cost Analysis**
A quarterly chart comparing:
- Unit Cost  
- Cost of Sales  

This helps identify:
- Cost spikes  
- Efficiency gains  
- Year-over-year trends  

Covers quarters from **Q4 2021 through Q3 2024**.

---

## 🛠 Tools & Technologies Used
- **Looker Dashboard (Google Cloud Looker)**  
- Looker Explores (for querying aggregated metrics)  
- Dashboard Filters (Region, Product Group, etc.)  
- Looker Visualizations:
  - Single Value Tiles  
  - Bar Charts  
  - Line & Combo Charts  
  - Trend Visualizations  
- Connected SQL Warehouse powering the explore  

> No custom LookML files are required — the dashboard uses existing explores in Looker.

---

## 📁 Recommended Repository Structure

```
Finance-Analytics-Looker-Dashboard/
│
├── README.md
├── Data/
│     └── Sales.xlsx
└── preview/
      ├── Finance_Analytics_Dashboard.png
```

---

## 📸 Dashboard Preview

```
![Finance Dashboard](screenshots/finance_dashboard.png)
```

---

## 🚀 How to Use
1. Open the dashboard in Looker.  
2. Adjust filters such as **Region** to refine financial insights.  
3. Hover, drill down, or view underlying data for deeper exploration.  
4. Export dashboards or schedule data delivery if needed.  

---

## 🎯 Summary

This Finance Analytics Dashboard offers a powerful, interactive way to track financial KPIs, monitor product and country performance, analyze promotional impact, and evaluate cost trends — all powered by Looker’s modeling layer and visualization capabilities.
