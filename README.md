# 🛒 Retail Business Analysis Dashboard | Power BI

## 📌 Overview
Transformed raw retail transactional data into actionable business
insights using Power BI and Advanced DAX.

---

## 📊 Dashboard Screenshots

### Page 1 – Sales Analysis
![Sales Analysis](powerbi/page1_sales.png)

### Page 2 – Profit Analysis
![Profit Analysis](powerbi/page2_profit.png)

### Page 3 – Demographics
![Demographics](powerbi/page3_demographis.png)

---

## 🎯 Key Results
- 📈 51% YoY Sales Growth identified
- 🏆 Top revenue-driving categories uncovered
- 💎 High-value customer segments discovered
- 🌐 Region-wise performance benchmarked

---

## ⚙️ DAX Measures
```DAX
Total Sales = SUM(Sales[Sales Amount])
PY Sales = CALCULATE([Total Sales], SAMEPERIODLASTYEAR(Date[Date]))
YoY Growth % = DIVIDE([Total Sales] - [PY Sales], [PY Sales])
```

---

## 🛠 Tools Used
| Tool | Usage |
|------|-------|
| Power BI | Dashboard & Visualization |
| DAX | KPI & Metric Engineering |
| Data Modeling | Table Relationships |
| Time Intelligence | YoY Trend Analysis |

---

## 📁 Dataset
- Source: Global Retail Sales Data
- File: `dataset/global_retail_sales_data.xlsx`
