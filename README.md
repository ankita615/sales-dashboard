# 📊 Task 2 – Data Visualization and Storytelling

## 📝 Project Title:
**Sales Performance Dashboard using Power BI**

## 📁 Dataset:
- [Sample_Superstore_Data.csv](./Sample_Superstore_Data.csv)
  - Contains fields such as Order Date, Region, Category, Sales, Profit, Quantity, and Segment.

---

## 🛠️ Tools Used:
- **Power BI Desktop**
- **DAX** (for calculated measures)
- **Custom visuals & filters**

---

## 📈 Key Measures Created (DAX):
```DAX
Total Sales = SUM('Table'[Sales])
Total Profit = SUM('Table'[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
Total Orders = DISTINCTCOUNT('Table'[Order ID])
