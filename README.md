# 📊 Financial Forecasting Dashboard using Power BI

This project presents an interactive **Financial Forecasting Dashboard** developed using Microsoft Power BI. It focuses on visual analytics, forecasting, and KPI-based insights for business performance.

---

## 🚀 Project Overview

Financial forecasting is a key element in business decision-making. This dashboard uses historical data to forecast future trends in sales, revenue, and profitability. Power BI's powerful visualization and data modeling capabilities are used to convert complex data into intuitive and actionable dashboards.

---

## 📌 Key Features

- 🔄 **Time-Series Forecasting** using historical sales and profit data  
- 🧮 **DAX Calculations** to derive KPIs like Total Revenue, Profit Margin, Forecasted Revenue  
- 🧹 **Power Query Data Cleaning** and transformation pipeline  
- 📈 **Interactive Visuals** including slicers, bar/line charts, country and product filters  
- 🌍 **Regional Analysis** of profitability and returns  
- 💡 **Actionable Insights** for decision-making and strategy optimization  

---

## 🧰 Tools & Technologies

- **Microsoft Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query**  
- **Excel** (for raw data storage and preprocessing)  

---

## 📂 Project Structure

```
📁 Financial-Forecasting-Dashboard
│
├── 📄 Financial_Forecasting_Report.docx         # Detailed report of the project
├── 📊 Financial_Forecasting_Dashboard.pbix      # Power BI dashboard file
├── 📈 financial_data.xlsx                        # Dataset used for analysis
└── 📖 README.md                                  # Project summary and instructions
```

---

## 📈 DAX Formulas Used

```DAX
Total Profit = SUM(financials[Profit])
Total Revenue = SUM(financials[Sales])
Profit Margin = DIVIDE([Total Profit], [Total Revenue], 0)
Forecasted Revenue = [Total Revenue] * 1.10
```

---

## 📌 Key Insights

- **Paseo** is the best-selling product with a total sales value of **₹33.01M**.  
- **USA** leads in profitability, with France closely following.  
- The total **forecasted revenue** is approximately **₹128M**.  
- The **profit margin** stands at **14.23%**.  

---

## 🔮 Future Enhancements

- 🤖 Integrate **machine learning models** for predictive analytics  
- 🌐 Add **geospatial visualizations** using custom Power BI maps  
- ⏱️ Enable **real-time data refresh** via Power BI Service  
- 📣 Implement **custom alerts** for key metric changes  

---

## 📚 Learnings

- Real-world application of Power BI in business analytics  
- Importance of clean data modeling for effective forecasting  
- Leveraging DAX for dynamic KPI tracking and reporting  

---

