# 📱 Mobile Sales Analytics Dashboard | Power BI

## 📌 Project Overview

The **Mobile Sales Analytics Dashboard** is an interactive business intelligence project developed using Microsoft Power BI to analyze mobile phone sales performance, transaction trends, customer ratings, payment preferences, and product-level insights.

The dashboard transforms sales data into meaningful visualizations and key performance indicators (KPIs), helping users monitor business performance, identify monthly sales patterns, compare sales across different periods, and understand customer purchasing behavior.

The project includes an interactive sales dashboard, a same-period-last-year comparison report, and a month-to-date (MTD) report.

## 🎯 Project Objectives

- Monitor total sales, quantities sold, average selling price, and transaction volume.
- Analyze monthly, quarterly, and yearly sales performance.
- Compare current sales with the same period in the previous year.
- Identify top-performing mobile brands and models.
- Understand customer preferences for different payment methods.
- Analyze customer ratings and satisfaction patterns.
- Explore sales distribution across cities and days of the week.
- Build interactive reports for business performance monitoring.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and reporting
- **Power Query** — Data transformation and preparation
- **DAX** — KPI calculations, time intelligence, and sales measures
- **Data Visualization** — Interactive charts, maps, and tables
- **Business Intelligence** — Sales performance analysis

## 📊 Dashboard Features

### 1. Mobile Sales Dashboard

The main dashboard provides an overview of mobile sales performance through the following KPIs:

| KPI | Displayed Value |
|---|---:|
| Total Sales | 769M |
| Total Quantity Sold | 19K |
| Average Price | 40.11K |
| Total Transactions | 4K |

*These values are taken from the dashboard screenshots and may be rounded. The exact units and calculations depend on the underlying dataset.*

**Visualizations include:**
- Monthly quantity sold trends
- City-wise sales distribution
- Customer ratings: Good, Average, and Poor
- Transactions by payment method
- Sales by mobile brand
- Sales by mobile model
- Sales by day of the week

### 2. Same Period Last Year Analysis

This report compares sales performance across the current and previous periods.

**Key features:**
- Year-wise sales comparison
- Quarter-wise sales comparison
- Month-wise sales comparison
- Current sales vs. same-period-last-year metrics
- Detailed table with year, quarter, sales, and comparison values

This analysis helps identify changes in sales performance over time and supports year-over-year business comparisons.

### 3. Month-to-Date (MTD) Report

The MTD report focuses on sales performance at a monthly level.

**Key features:**
- Monthly sales trends
- MTD sales calculations
- Year, quarter, and month breakdowns
- Detailed monthly sales table
- Interactive date and category filters

The report helps track monthly performance and monitor sales progress within the selected reporting period.

## 🔍 Interactive Filters

The dashboard provides filters and navigation controls for exploring the data.

- **Mobile Model** — Analyze sales for selected models.
- **Brand** — Compare mobile brands.
- **Payment Method** — Examine payment preferences.
- **Year, Quarter, Month, and Day** — Explore performance across time.
- **Month Navigation** — Focus on specific months.
- **Report Navigation** — Switch between dashboard views and sales reports.

## 💡 Business Insights

The dashboard is designed to help answer important business questions:

1. How do mobile sales and quantities change from month to month?
2. Which mobile brands and models contribute most to sales?
3. Which payment methods are used most frequently?
4. How do sales vary across cities and days of the week?
5. How do customer ratings vary across the dataset?
6. How does current sales performance compare with the same period last year?
7. Which months and quarters show stronger or weaker sales performance?

These questions can help business teams investigate sales trends, product demand, customer preferences, and opportunities for improvement.

## 🎨 Dashboard Design

The dashboard uses a blue-and-white theme with KPI cards, clear chart layouts, and interactive controls.

Key design elements include:
- KPI cards for high-level performance monitoring
- Line charts for monthly sales and quantity trends
- Bar charts for product and time-based comparisons
- Pie charts for payment method distribution
- Geographic maps for city-level analysis
- Tables for detailed sales reporting
- Interactive slicers and report navigation

## 📷 Dashboard Preview

### Main Mobile Sales Dashboard

![Mobile Sales Dashboard](https://github.com/Hardixkk/Mobile-Sales-dashboard-/blob/main/Sales%20Dashboard.png)

### Same Period Last Year Report

![Same Period Last Year Report](https://github.com/Hardixkk/Mobile-Sales-dashboard-/blob/main/Year%20wise%20sales.png)

### Month-to-Date Report

![MTD Sales Report](screenshots/mtd-sales-report.png)

*Upload the three screenshots to the `screenshots` folder using these filenames, or change the paths to match your actual filenames.*

## 📁 Suggested Repository Structure

```text
Mobile-Sales-Analytics-PowerBI/
│
├── README.md
├── Mobile_Sales_Analytics.pbix
├── dataset/
│   └── mobile_sales_data.csv
└── screenshots/
    ├── mobile-sales-dashboard.png
    ├── same-period-last-year.png
    └── mtd-sales-report.png
```

*This is a suggested structure. Include only the files available in your project and update the filenames accordingly.*

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install Microsoft Power BI Desktop.
3. Open the `.pbix` file in Power BI Desktop.
4. If prompted, update the data source path to the location of your dataset.
5. Refresh the data if required.
6. Navigate between the dashboard, previous-year comparison, and MTD report.
7. Use the filters and slicers to explore sales performance.

## 🔮 Future Enhancements

- Add product profitability and profit margin analysis.
- Develop detailed brand and model rankings.
- Include customer segmentation and purchase frequency analysis.
- Add sales forecasting and trend prediction.
- Improve drill-through analysis for individual products and cities.
- Automate data refresh where the data source supports it.

## 👨‍💻 Author

**Hardik Kumar Singh**

BCA Student | Aspiring Data Analyst

**Areas of Interest:** Power BI, SQL, Excel, Business Intelligence, and Data Analytics.

## ⭐ Acknowledgements

This project was developed as a practical data analytics portfolio project to strengthen skills in data modeling, dashboard design, KPI reporting, time-based analysis, and interactive business intelligence using Microsoft Power BI.

If you find this project useful, consider giving the repository a ⭐ on GitHub.

## ⚠️ Disclaimer

This dashboard is intended for educational and portfolio demonstration purposes. Business conclusions depend on the quality of the underlying dataset, the accuracy of the measures, and the selected filters.
