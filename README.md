# BlinkIT Grocery Sales Analysis (Excel & Power BI)

This project explores grocery sales data from BlinkIT using Excel for cleaning and Power BI for analysis and visualization.  
The goal was to understand sales patterns, product performance, outlet behavior, and key factors that influence overall revenue.

---

## 🔗 Live Power BI Dashboard  
You can view the interactive dashboard here:  
➡️ **[Click here to see the live dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDUxNzMzMjMtMDY2Zi00MjlkLTgyZTYtZGYzNmQwMzZiNGQxIiwidCI6IjUwMTliMDA3LWRkZDUtNGIzNS05MjNiLTNmZDcwNzU1OTYyNCJ9)**

---

## 📁 Project Structure

```
blinkit_grocery_sales_analysis_powerbi_excel/
│
├── data/
│ ├── BlinkIT Grocery Data.xlsx
│ └── BlinkIT Grocery Data.csv
│
├── images/
│ └── dashboard-preview.png
│
└── README.md
```


---

## 🧠 Objectives of the Analysis

- Clean and prepare the grocery sales dataset  
- Explore sales and rating patterns  
- Compare outlet performance across sizes and locations  
- Analyze the impact of fat content and item types on sales  
- Build a structured, interactive Power BI dashboard  
- Summarize key insights that can support business decisions  

---

## 🧹 Data Cleaning (Excel)

Below are the main steps taken during the cleaning process:

- Removed missing and inconsistent values  
- Standardized categorical fields  
- Checked and corrected data types  
- Ensured numeric columns such as sales, item weight, and visibility were valid  
- Cleaned text fields and simplified category names  

---

## 📊 Sample Dataset Preview

A small preview of the dataset used in this analysis:

| Sr No | Fat Content | Item Identifier | Item Type               | Outlet Establishment Year | Outlet Identifier | Outlet Location Type | Outlet Size | Outlet Type          | Item Visibility | Item Weight | Sales    | Rating |
|-------|-------------|-----------------|--------------------------|----------------------------|--------------------|------------------------|-------------|-----------------------|-----------------|-------------|----------|--------|
| 1     | Regular     | FDX32           | Fruits and Vegetables    | 2012                       | OUT049             | Tier 1                | Medium      | Supermarket Type1     | 0.100014        | 15.10       | 145.48   | 5.0    |
| 2     | Low Fat     | NCB42           | Health and Hygiene       | 2022                       | OUT018             | Tier 3                | Medium      | Supermarket Type2     | 0.008596        | 11.80       | 115.35   | 5.0    |
| 3     | Regular     | FDR28           | Frozen Foods             | 2016                       | OUT046             | Tier 1                | Small       | Supermarket Type1     | 0.025896        | 13.85       | 165.02   | 5.0    |
| 4     | Regular     | FDL50           | Canned                   | 2014                       | OUT013             | Tier 3                | High        | Supermarket Type1     | 0.042278        | 12.15       | 126.50   | 5.0    |
| 5     | Low Fat     | DRI25           | Soft Drinks              | 2015                       | OUT045             | Tier 2                | Small       | Supermarket Type1     | 0.033970        | 19.60       | 55.16    | 5.0    |

The full dataset can be found in the `data` folder.

---

## 📈 Dashboard Highlights

### **1. Key Performance Indicators**
- Total Sales: **$1.20M**  
- Average Sales: **$141**  
- Total Items: **8523**  
- Average Rating: **4.0**  

### **2. Outlet Performance**
- Medium-sized outlets generate the highest revenue  
- Tier 3 outlets outperform Tier 1 and Tier 2  
- Supermarket Type 1 contributes the most to overall sales  

### **3. Product-Level Insights**
- Fruits & Vegetables and Snack Foods are the top-selling item categories  
- Regular fat products account for most of the sales  
- Sales peaked around 2018, showing a strong annual trend  

---

## 🛠 Tools Used

- **Microsoft Excel** – data cleaning and preprocessing  
- **Power BI** – dashboard design and analysis  
- **Power Query** – transformations and data shaping  
- **DAX** – custom measures and KPIs  

---

## 🚀 Future Improvements

- Adding forecasting models inside Power BI  
- Including customer segmentation based on purchasing patterns  
- Automating data refresh through Power BI Service  
- Adding advanced visuals using Python/R in Power BI  

---

## 👤 Author

**Ankur Saha**  
Aspiring Data Analyst  
Excel • SQL • Power BI  
