# BlinkIT Grocery Sales Data Analysis (Excel + Power BI)
*A Data Analytics Project by Ankur Saha*  

[![Power BI Dashboard](https://img.shields.io/badge/Live-Dashboard-yellow?logo=Power%20BI)](https://app.powerbi.com/view?r=eyJrIjoiNDUxNzMzMjMtMDY2Zi00MjlkLTgyZTYtZGYzNmQwMzZiNGQxIiwidCI6IjUwMTliMDA3LWRkZDUtNGIzNS05MjNiLTNmZDcwNzU1OTYyNCJ9)
[![Made with Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-green?logo=microsoft-excel)]()
[![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?logo=powerbi)]()

---

## 📌 Project Overview

This project analyzes **BlinkIT grocery sales data** using **Microsoft Excel** for data cleaning and **Power BI** for dashboard creation.  
The aim is to understand revenue trends, product performance, outlet behavior, and customer preferences to support **data-driven decision making**.

---

## 🔗 Live Interactive Dashboard (View Only — Protected)

👉 **Click here to view the live Power BI Dashboard**  
### https://app.powerbi.com/view?r=eyJrIjoiNDUxNzMzMjMtMDY2Zi00MjlkLTgyZTYtZGYzNmQwMzZiNGQxIiwidCI6IjUwMTliMDA3LWRkZDUtNGIzNS05MjNiLTNmZDcwNzU1OTYyNCJ9

✔ View-only  
✔ PBIX file hidden  
✔ Data protected  
✔ Perfect for portfolio  

---

## 📂 Project Structure

blinkit-grocery-sales-analysis/
│
├── data/
│ ├── BlinkIT Grocery Data.xlsx
│ └── BlinkIT Grocery Data.csv
│
├── images/
│ └── dashboard-preview.png
│
└── README.md

yaml
Copy code

---

## 🎯 Project Objectives

- Perform data cleaning using Excel  
- Build an interactive Power BI dashboard  
- Identify KPIs, trends, and patterns  
- Analyze outlet performance across size and location  
- Compare product types and fat content categories  
- Extract actionable business insights  

---

## 🧹 Data Cleaning (Excel)

Cleaning steps performed:

- Removed missing & inconsistent values  
- Standardized text categories (fat content, outlet type, etc.)  
- Verified numeric data (MRP, visibility, weight, sales)  
- Removed duplicates  
- Ensured dataset quality before Power BI import  

---

## 📁 Sample Dataset Preview

Below is a preview of the first few rows of the BlinkIT grocery sales dataset used for analysis:

| Sr No | Fat Content | Item Identifier | Item Type               | Outlet Establishment Year | Outlet Identifier | Outlet Location Type | Outlet Size | Outlet Type          | Item Visibility | Item Weight | Sales    | Rating |
|-------|-------------|-----------------|--------------------------|----------------------------|--------------------|------------------------|-------------|-----------------------|-----------------|-------------|----------|--------|
| 1     | Regular     | FDX32           | Fruits and Vegetables    | 2012                       | OUT049             | Tier 1                | Medium      | Supermarket Type1     | 0.100014        | 15.10       | 145.48   | 5.0    |
| 2     | Low Fat     | NCB42           | Health and Hygiene       | 2022                       | OUT018             | Tier 3                | Medium      | Supermarket Type2     | 0.008596        | 11.80       | 115.35   | 5.0    |
| 3     | Regular     | FDR28           | Frozen Foods             | 2016                       | OUT046             | Tier 1                | Small       | Supermarket Type1     | 0.025896        | 13.85       | 165.02   | 5.0    |
| 4     | Regular     | FDL50           | Canned                   | 2014                       | OUT013             | Tier 3                | High        | Supermarket Type1     | 0.042278        | 12.15       | 126.50   | 5.0    |
| 5     | Low Fat     | DRI25           | Soft Drinks              | 2015                       | OUT045             | Tier 2                | Small       | Supermarket Type1     | 0.033970        | 19.60       | 55.16    | 5.0    |

> **Note:** Full dataset available in the `/data` folder.

---

## 📊 Dashboard Highlights (Power BI)

### **Key KPIs**
- **$1.20M** – Total Sales  
- **$141** – Average Sales  
- **8523** – Total Items  
- **4.0** – Average Rating  

---

## 📈 Key Insights

### **1️⃣ Outlet Size Performance**
- Medium outlets generate the highest sales (**42.27%**).  
- High outlets follow at **37%**.  
- Small outlets contribute **20.7%**.

### **2️⃣ Fat Content Insights**
- Regular fat products dominate (64.6% of total revenue).  
- Low-fat contributes roughly ~$425K.

### **3️⃣ Location Tier Performance**
- **Tier 3** outlets perform best (~$507K).  
- **Tier 1** outlets perform the lowest (~$336K).

### **4️⃣ Product Type Revenue Leaders**
- Fruits & Vegetables — **$178K**  
- Snack Foods — **$175K**  
- Household — **$136K**  
- Frozen Foods — **$119K**

### **5️⃣ Outlet Type Breakdown**
- Supermarket Type 1 is the highest contributor (~$788K).  
- Grocery stores generate the lowest revenue.

### **6️⃣ Yearly Sales Trends**
- Sales peak around **2018 (~$204K)**.  

---

## 🛠 Tools & Technologies

- **Excel** — Data cleaning & preprocessing  
- **Power BI** — Dashboard, data modeling, DAX  
- **DAX Measures** — KPIs and calculations  
- **Power Query** — Transformations  

---

## 📥 How to Use This Project

1. Open the **live dashboard** using the link above  
2. Explore KPIs, slicers, and insights  
3. Review the dataset and cleaning steps in this repository  

*(PBIX file intentionally not included to protect dashboard design.)*

---

## 🚀 Future Enhancements

- Add forecasting using Power BI  
- Build customer segmentation models  
- Automate refresh in Power BI Service  
- Add R/Python visuals for deeper analysis  

---

## 👤 Author

**Ankur Saha**  
Aspiring Data Analyst  
Excel | SQL | Power BI  
