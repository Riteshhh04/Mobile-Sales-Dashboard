# 📊 Mobile Sales Dashboard - Power BI Project

This Power BI project presents a dynamic and insightful dashboard analyzing mobile phone sales data across India. It includes monthly trends, city-wise sales, model-wise comparisons, customer ratings, and performance tracking against the Same Period Last Year (SPLY).

---

## 🔧 Features

- ✅ Cleaned and transformed raw sales data using **Power Query**
- 📅 Created a **Custom Calendar Table** for accurate time intelligence
- 📈 Developed **Month-To-Date (MTD)** and **Same Period Last Year (SPLY)** reports using DAX
- 🌍 Geo map visualization showing **Total Sales by City**
- 📊 Visual comparisons across **brands**, **mobile models**, **payment methods**, and **ratings**

---

## 📸 Dashboard Views

1. **Main Dashboard** – Overview of sales performance with slicers for filters
2. **MTD Report** – Month-To-Date trend line with daily sales
3. **SPLY Comparison** – Bar charts showing current vs previous year sales by month & quarter

---

## 🧠 Key DAX Measures

- `Total Sales`
- `Total Quantity`
- `Average Price`
- `MTD Sales = TOTALMTD([Total Sales], 'Calendar'[Date])`
- `SPLY Sales = CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Calendar'[Date]))`

---

## 💻 Tools Used

- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- **Excel** (for data pre-processing)

---

## 🚀 How to Use This Project

1. **Download the Project Files**
   - Clone the repo or download the `Mobile Sales Dashboard.pbix` file from this repository.

2. **Open in Power BI Desktop**
   - Make sure [Power BI Desktop](https://powerbi.microsoft.com/desktop/) is installed on your system.
   - Open the `.pbix` file.

3. **Load Your Data**
   - Replace the existing data source with your own if needed.
   - Refresh the data to see the latest updates.

4. **Explore and Customize**
   - Use filters to view sales by brand, model, payment method, or date.
   - Check Month-To-Date trends and compare sales with the same period last year.

---

## 📈 Insights Delivered

- 📊 Sales growth trends by month and region
- 🔝 Best-performing brands and models
- 💳 Preferred payment methods
- 🎯 Comparison with previous year's performance
- ⭐ Customer rating analysis

---

> 💡 Feel free to fork this repo, customize visuals, or use it for practice, learning, or your own business reports!

