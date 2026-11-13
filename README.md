
# 📊 Business Pulse – Interactive Business Analytics Dashboard | Power BI

## 📌 Project Overview

**Business Pulse** is an interactive Business Intelligence and Data Analytics project developed using Microsoft Power BI. The main objective of this project is to transform raw business transaction data into meaningful visual insights that help understand sales performance, profitability, expenses, customer behaviour, and market trends.

The dashboard provides a comprehensive overview of business performance using interactive visualizations, KPI cards, charts, and dynamic filters. It enables users to explore business data from different perspectives and identify trends, opportunities, and areas that require improvement.

This project uses a Superstore business dataset covering transactions from 2011 to 2015.

## 🎯 Project Objectives

- Analyse overall business sales and profitability.
- Monitor business performance using interactive KPI indicators.
- Understand monthly, yearly, and daily sales trends.
- Identify profitable and loss-making product categories.
- Analyse sales performance across different geographical markets.
- Evaluate shipping costs and shipping methods.
- Understand customer segment contributions to total sales.
- Identify business opportunities through data-driven insights.
- Support better business decisions using interactive dashboards.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and data visualization |
| Power Query | Data preparation and transformation |
| DAX (Data Analysis Expressions) | Calculated measures and business metrics |
| Superstore Dataset | Business transaction data |
| Data Visualization | Interactive charts, graphs, and KPI cards |

## 📂 Dashboard Structure

The project consists of two interactive dashboard pages.

### 1. Business Dashboard

The first page provides a high-level overview of the company's overall business performance.

**Key Performance Indicators (KPIs):**

- Total Sales – Measures the overall revenue generated.
- Total Profit – Displays the total profit earned.
- Shipping Cost – Tracks the total shipping expenses.
- Total Orders – Counts the number of transactions.
- Total Quantity – Displays the total quantity of products sold.
- Total Customers – Measures the number of customer records.

**Visualizations:**

- Sales and Profit Analysis – Compares yearly and monthly sales and profit performance.
- Sales Trend Analysis – Tracks sales across different time intervals, including year, quarter, month, and day.
- Market Performance – Compares sales and profit across geographical markets.
- Category Analysis – Displays sales distribution across product categories.
- Sub-Category Profitability – Identifies the most profitable and loss-making product sub-categories.

**Interactive Filters:**

- Order Date
- Month
- Product Category
- Shipping Mode
- Market

These filters allow users to dynamically explore the dashboard and analyse specific business periods or segments.

### 2. Costs, Transactions & Insights

The second page focuses on business costs, transaction-level information, and actionable business insights.

**Key Visualizations:**

- Shipping Cost Analysis – Evaluates shipping expenses across different shipping methods.
- Category Performance – Compares sales, profit, and shipping costs across product categories.
- Customer Segment Analysis – Examines sales contributions from different customer segments.
- Transaction Details – Provides detailed transaction-level information, including order date, order ID, customer name, product name, market, sales, and profit.

**Business Insights:**

The dashboard also includes a dedicated insights section highlighting important business findings and recommendations based on the dataset.

## 📈 Key Business Insights

Based on the analysed dataset, the dashboard highlights the following findings:

| Business Metric | Result |
|---|---:|
| Total Sales | $12.64 Million |
| Total Expenses* | $11.18 Million |
| Total Profit | $1.47 Million |
| Profit Margin | 11.6% |
| Leading Market | APAC |
| APAC Sales Contribution | 28.4% |
| Highest Sales Month | November 2014 |
| Highest Monthly Sales | $555.3K |
| Highest Expense Sub-Category | Phones ($1.49M) |

**Additional Findings:**

- Annual profit increased consistently from 2011 to 2014.
- Tables recorded a loss of approximately $64.1K.
- Accessories achieved a profit margin of approximately 17.3%.
- Copiers achieved a profit margin of approximately 17.1%.
- EMEA recorded the lowest market profit margin at approximately 5.4%.
- Shipping costs accounted for approximately 10.7% of total sales.
- Sales generally peaked in December and declined in February.

*Note: Expenses are calculated as Sales minus Profit in this project. This is a derived business metric based on the dataset, rather than a separately recorded expense ledger.*

## 🧮 DAX Calculation

The project uses DAX to calculate important business metrics.

**Total Expenses:**

```dax
Total Expenses =
SUM('superstore_dataset2011-2015'[Sales])
-
SUM('superstore_dataset2011-2015'[Profit])
```

This measure calculates the difference between total sales and total profit to estimate expenses.

Other dashboard KPIs use aggregations such as SUM and COUNT over the relevant dataset columns.

## 💡 Business Recommendations

Based on the dashboard analysis, the following recommendations can help improve business performance:

1. Review pricing strategies and discount policies for loss-making product categories, particularly Tables.
2. Focus on high-margin product categories such as Accessories and Copiers.
3. Evaluate shipping costs and encourage cost-effective shipping methods.
4. Review discounting and pricing strategies in the EMEA market.
5. Prepare inventory in advance of peak sales periods, particularly December.
6. Introduce targeted promotions during lower-sales periods such as February.

## 📊 Skills Demonstrated

Through this project, I demonstrated practical knowledge of:

- Business Intelligence and Data Analytics
- Data Cleaning and Data Transformation
- Power BI Dashboard Development
- Data Visualization and Reporting
- DAX Measures and Calculations
- KPI Development
- Sales and Profitability Analysis
- Trend Analysis
- Market and Customer Segmentation
- Interactive Data Filtering
- Business Insights and Decision Support

## 📁 Project Files

```text
Business-Pulse-Dashboard/
│
├── Business-Pulse-Dashboard.pbix
│
├── README.md
│
└── Screenshots/
    ├── Business-Dashboard.png
    └── Costs-Insights.png
```

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open `Business-Pulse-Dashboard.pbix`.
4. Explore the two dashboard pages.
5. Use the interactive slicers to filter the business data.
6. Analyse the visualizations and business insights.

**Note:** If the original dataset is not embedded or available in the PBIX file, the source dataset must also be provided to refresh the report.

## 🔮 Future Enhancements

Potential improvements for future versions include:

- Adding dedicated cash flow analysis.
- Developing more detailed expense tracking.
- Introducing year-over-year growth comparisons.
- Adding customer retention and purchasing behaviour analysis.
- Developing sales forecasting using machine learning.
- Adding advanced geographical visualizations.
- Integrating real-time business data.

## 👨‍💻 Author

**Mohammed Shameel PK**

Bachelor's in Computer Science

Interested in Data Analytics, Business Intelligence, Data Visualization, and Data Science.

---

⭐ If you find this project useful, feel free to explore the dashboard and its visualizations.

**Project Name:** Business Pulse – Business Analytics Dashboard  
**Platform:** Microsoft Power BI  
**Domain:** Data Analytics & Business Intelligence  
**Dataset Period:** 2011–2015
