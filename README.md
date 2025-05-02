# 📊 Superstore Sales Dashboard

## 🧾 Project Overview
This project presents a **simple, interactive sales dashboard** built using **Power BI**, aimed at visualizing sales performance by **product category**, **region**, and **month**. The dashboard provides a clear summary for business decision-makers to track trends, identify top-performing areas, and spot opportunities for growth.

---

## 🛠 Tools Used
- **Power BI Desktop**

## 📁 Dataset
- **File Name**: Superstore_Sales_Dataset.csv
- **Key Columns**:
  - `Order Date`
  - `Region`
  - `Category`
  - `Sales`
  - `Profit`

---

## 📌 Dashboard Features
1. **Line Chart** – Sales trend across months (`Month-Year`)
2. **Bar Chart** – Sales comparison by `Sub-Category`
3. **Donut Chart** – Proportional sales by `Category`
4. **Pie Chart** - Profit by `Payment Mode`
5. **Slicer Filter** – Interactively filter data by `Region`
6. **Conditional Formatting** – Colors highlight top-performing areas

---

## 🧠 Key Insights
- The **West region** consistently led in total sales, especially peaking in Q3.
- The **Technology category** outperformed Furniture and Office Supplies.
- **December** recorded the highest monthly sales.
- **Central region** had the most balanced distribution of sales across categories.

## 📌 Notes
- The `Order Date` field was transformed to `Month-Year` format using:
  ```DAX
  MonthYear = FORMAT('Table'[Order Date], "MMMM YYYY")

