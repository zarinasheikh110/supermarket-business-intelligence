# 🛒 Supermarket Business Intelligence Dashboard | Power BI

## 📌 Project Overview

The **Supermarket Business Intelligence Dashboard** is an interactive Power BI project designed to analyze supermarket sales, store performance, product categories, customer behavior, promotional effectiveness, and inventory risks.

Developed using **Microsoft Power BI, DAX, and data visualization techniques**, this project transforms raw business data into meaningful insights to support data-driven decision-making, improve operational efficiency, and enhance profitability.

## 🎯 Project Objectives

- Analyze overall sales performance and profitability.
- Evaluate store-level and regional performance.
- Identify top-performing and underperforming product categories.
- Understand customer segments and purchasing behavior.
- Measure promotional effectiveness and discount impact.
- Monitor stockouts, inventory waste, and potential losses.
- Support strategic planning through interactive dashboards.

## 🛠️ Tools and Technologies

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Data Modeling and Relationships
- Interactive Data Visualization
- KPI Development and Performance Monitoring
- GitHub for Project Documentation

## 📊 Dashboard Pages

### 1. Landing Page
A professional navigation interface providing access to the dashboard's analytical modules.

### 2. Executive Overview
Provides a consolidated view of overall supermarket performance.

**Key KPIs and Visualizations:**
- Total Revenue
- Net Profit
- Profit Margin %
- Total Transactions
- Average Basket Value
- Revenue and Net Profit Trends
- Revenue by Region
- Transaction Volume by Region
- Revenue by Category
- Top 10 Products by Revenue

### 3. Store Performance
Evaluates store-level profitability, regional contributions, and operational performance.

**Key KPIs and Visualizations:**
- Total Stores
- Total Revenue
- Net Profit
- Profit Margin %
- Average Revenue per Store
- Revenue vs. Net Profit by Store
- Monthly Revenue Trends
- Store Performance Summary
- Regional Revenue and Profitability
- Revenue by Sales Channel

### 4. Category & Product Performance
Analyzes category-level sales, product performance, and profitability.

**Key KPIs and Visualizations:**
- Total Categories
- Total Quantity Sold
- Average Basket Value
- Promotion Share
- Top Product and Least Product
- Revenue by Category
- Net Profit Contribution by Category
- Top 10 Products by Revenue
- Profit Margin by Category
- Product Revenue vs. Net Profit Performance
- Revenue Distribution by Category

### 5. Customer & Channel Insights
Examines customer segments, purchasing patterns, sales channels, and payment preferences.

**Key KPIs and Visualizations:**
- Total Revenue
- Total Transactions
- Net Profit
- Active Customer Segments
- Average Basket Value
- Channel Revenue
- Revenue by Customer Segment
- Transactions by Customer Segment
- Average Basket Value by Segment
- Revenue Comparison by Customer Segment
- Revenue and Net Profit by Sales Channel
- Transactions by Payment Method
- Segment Spending by Product Category

### 6. Promotion Effectiveness
Measures the impact of promotional campaigns and discounts on sales and profitability.

**Key KPIs and Visualizations:**
- Promotional Sales
- Non-Promotional Sales
- Average Discount %
- Promotion Share %
- Promotional Net Profit
- Promotional Profit Margin %
- Quantity Sold During Promotions
- Profit Margin by Promotion Type
- Category Promotion Dependency
- Sales by Promotion Type
- Top Products by Promotional Sales
- Promotional vs. Non-Promotional Sales Trends

### 7. Inventory Risk & Waste
Monitors inventory availability, stockout incidents, waste costs, and operational risks.

**Key KPIs and Visualizations:**
- Stockout Rate
- Stockout Incidents
- Lost Sales Risk
- Waste Cost
- Waste Cost % of Sales
- Fresh and Chilled Product Waste
- Stockout Rate by Category
- Stockout Incidents by Store
- Waste Cost Trend
- Waste Cost by Storage Type
- Top Fresh and Chilled Products by Waste Cost
- Store and Category Risk Matrix

### 8. Tooltip and Supporting Pages
Includes supporting report pages such as **Tooltip – Region** and **Tooltip – Monthly Trend** to provide additional contextual insights when interacting with visualizations.

## 📈 Key Business Insights

The dashboard supports analysis of:

- Monthly sales and profitability trends.
- Regional and store-level performance differences.
- High-revenue products and profitable product categories.
- Customer segment spending and transaction behavior.
- Promotional sales performance and discount effectiveness.
- Inventory shortages and potential lost sales.
- Waste costs and opportunities to improve inventory management.

*Business conclusions should be validated against the underlying dataset and the filters applied to the report.*

## 🎛️ Interactive Dashboard Features

- Dynamic slicers and filters.
- Interactive KPI cards.
- Cross-filtering between visualizations.
- Custom page navigation buttons.
- Drill-through functionality where configured.
- Tooltip pages for additional analytical details.
- Conditional formatting and performance comparisons.
- Inventory risk indicators.
- Sales, customer, product, and promotion analysis.

## 🗂️ Data Model

The project includes the following primary tables:

| Table Name | Purpose |
|---|---|
| Transactions | Sales, revenue, profit, and transaction analysis |
| Products | Product information and category analysis |
| Stores | Store details and regional analysis |
| KPI Targets | Business targets and performance comparisons |
| KPI Dictionary | KPI definitions and calculation references |
| Dashboard Requirements | Dashboard specifications and requirements |

## 🧮 DAX Measures

DAX measures are used to calculate important business metrics.

**Total Revenue**

```dax
Total Revenue =
SUM(Transactions[Total_Revenue])
```

**Net Profit**

```dax
Net Profit =
SUM(Transactions[Net_Profit])
```

**Profit Margin %**

```dax
Profit Margin % =
DIVIDE(
    [Net Profit],
    [Total Revenue],
    0
) * 100
```

*Note: These sample formulas assume the specified column names exist in the Transactions table. Adjust them to match your actual data model.*

## 🚀 How to Explore the Project

1. Visit the GitHub repository.
2. Review the project documentation and dashboard images displayed in the repository.
3. Download the Power BI `.pbix` file if available.
4. Open the file using Microsoft Power BI Desktop.
5. Explore the report pages, interactive filters, KPI measures, and visualizations.

## 💡 Skills Demonstrated

- Business Intelligence and Data Analytics
- Data Cleaning and Transformation
- DAX Calculations and Measure Development
- Data Modeling
- KPI Design and Monitoring
- Sales and Profitability Analysis
- Customer Segmentation
- Promotional Effectiveness Analysis
- Inventory Risk and Waste Analysis
- Interactive Dashboard Development
- Data Storytelling and Visualization

  ## Dashboard Preview

### 1. Landing Page
![Landing Page](dashboard-screenshots/01-Landing-Page.png)

### 2. Landing Page 2
![Landing Page 2](dashboard-screenshots/02-Landing-Page-2.png)

### 3. Executive Overview
![Executive Overview](dashboard-screenshots/03-Executive-Overview.png)

### 4. Store Performance
![Store Performance](dashboard-screenshots/04-Store-Performance.png)

### 5. Category & Product Performance
![Category and Product Performance](dashboard-screenshots/05-Category-Product-Performance.png)

### 6. Customer & Channel Insights
![Customer and Channel Insights](dashboard-screenshots/06-Customer-Channel-Insights.png)

### 7. Promotion Effectiveness
![Promotion Effectiveness](dashboard-screenshots/07-Promotion-Effectiveness.png)

### 8. Inventory Risk & Waste
![Inventory Risk and Waste](dashboard-screenshots/08-Inventory-Risk-Waste.png)

## 👩‍💻 About the Author

**Zarina Sheikh**

Aspiring Business Intelligence and Data Analytics Professional with hands-on experience in Power BI dashboard development, DAX, KPI analysis, and interactive data visualization.

### Connect With Me

- **LinkedIn:** [Zarina Sheikh](https://www.linkedin.com/in/zarina-sheikh-590386420/)
- **GitHub Profile:** [zarinasheikh110](https://github.com/zarinasheikh110)
- **GitHub Project Repository:** [Supermarket Business Intelligence](https://github.com/zarinasheikh110/supermarket-business-intelligence)

## 📄 License

No license has been specified for this project. Add an appropriate open-source license if you intend to permit others to reuse or modify the project.

---

⭐ If you find this project useful, consider starring the repository on GitHub.

**Project Summary:** An interactive Power BI dashboard that transforms supermarket data into actionable business insights across sales, stores, products, customers, promotions, and inventory management.
