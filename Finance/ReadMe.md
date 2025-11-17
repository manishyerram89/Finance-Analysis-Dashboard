# Finance Analytics Dashboard

This Looker dashboard provides a complete financial performance overview using LookML-powered explores, interactive filters, and drillable visualizations. It analyzes key financial metrics such as sales, profit, cost, pricing, product performance, country-level contribution, promotions, and time‑based trends. The dashboard enables finance teams to explore aggregated and granular insights efficiently using Looker’s semantic modeling layer.

---

## 📌 Overview

This dashboard leverages **LookML explores, measures, and dimensions** to generate a unified financial analytics view. Users can filter by **Region** and drill into product lines, promotions, and categories to understand financial drivers.

Key metrics modeled in LookML include:
- **Total Sales:** $55.4M  
- **Total Profit:** $31.6M  
- **Sales Cost:** $23.8M  
- **Unit Cost:** $1.9M  
- **Price:** $4.4M  
- **Number of Products:** 1.6K  

These KPIs are calculated using LookML measures and surfaced as dashboard tiles.

---

## 📊 Dashboard Sections & Looker-Specific Insights

### **1. KPI Tiles (LookML Measures)**
The top section uses Looker single-value tiles powered by:
- Aggregated LookML measures  
- Conditional formatting  
- Region-level dashboard filters  

These provide instant visibility into financial performance.

---

### **2. Profit by Country**
A horizontal bar visualization built using:
- Country dimension  
- Profit measure  
- Sorting & pagination  

Allows drill-down into specific geographies through Looker drill paths.

---

### **3. Profit by Product Category**
A tile based on LookML explores that include:
- Product category dimension  
- Profit measure  

Useful for identifying top-performing product groups.

---

### **4. Profit by Product Sub-Category**
A deeper explore showing:
- Product sub-category dimension  
- Profit measure  

Supports drill-down to SKU-level data when configured in LookML.

---

### **5. Promotion-Level Profitability**
This tile uses:
- Promotion name dimension  
- Profit measure  
- Looker pivoting to compare promotions  

Shows which promotional campaigns contribute the most revenue.

---

### **6. Monthly Sales & Profit Trend**
A multi-series line+bar chart using:
- Month dimension group  
- Profit and Sales measures  

Reveals seasonal trends and misalignment between sales and profitability.

---

### **7. Quarterly Cost Analysis**
A bar chart comparing:
- Unit Cost measure  
- Cost of Sales measure  

Modeled in LookML to support quarter-based time grouping.

---

## 🛠 Tools & Technologies Used
- **Looker (Google Cloud Looker)**  
- **LookML Models** (explores, views, measures, dimensions)  
- **Dashboard Tiles** (single-value, bar, line, combo charts)  
- **Dashboard Filters** (Region, Product, Category)  
- **SQL Runner** (optional for validation)  
- Financial dataset connected via Looker’s database model  

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
![Dashboard Preview](screenshots/finance_dashboard.png)
```

---

## 🚀 How to Use
1. Open the dashboard in Looker.  
2. Apply filters (Region/Product) to explore metrics.  
3. Drill into visualizations to view row‑level data.  
4. Inspect LookML definitions for measures and dimensions.  
5. Export insights via Looker schedules or CSV exports.

---

## 🎯 Summary
This Looker Finance Analytics Dashboard delivers a complete financial intelligence layer powered by LookML. By combining KPIs, product-level profitability, promotional analysis, and time‑based cost evaluation, it provides a powerful foundation for data-driven financial planning and strategic decision‑making.

