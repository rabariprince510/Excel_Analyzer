# 📊 Sales Data Analyzer | Excel Analytics Dashboard

**An end-to-end sales data analysis project built using Microsoft Excel to transform raw sales records into meaningful business insights through KPI reporting, customer analysis, statistical analysis, and interactive visualizations.**

---

## 📌 Project Overview

The **Sales Data Analyzer** is an Excel-based data analytics project designed to analyze sales performance, profitability, customer purchasing behavior, discount sensitivity, and monthly sales trends.

The project combines Excel formulas, statistical techniques, conditional formatting, regression analysis, and pivot tables to support data-driven business decisions.

The workbook contains **200 sales records** and organizes the analysis into eight dedicated worksheets for efficient reporting and interpretation.

## 🎯 Project Objectives

- Analyze overall revenue, profit, and quantity sold.
- Identify top-performing customers and high-value customer records.
- Evaluate the potential impact of discount changes on profitability.
- Calculate descriptive statistics for important business metrics.
- Examine the relationship between sales and profit using linear regression.
- Track month-over-month sales growth and trends.
- Compare sales performance across regions and product categories.
- Present key performance indicators through a centralized dashboard.

## 🛠️ Tools & Technologies

- **Microsoft Excel** — Data analysis, calculations, and reporting.
- **Excel Formulas & Functions** — SUM, AVERAGE, STDEV.S, MEDIAN, MIN, MAX, COUNT, IF, INDEX, and MATCH.
- **Statistical Analysis** — Descriptive statistics and linear regression.
- **What-If Analysis** — Discount sensitivity and estimated profit scenarios.
- **Pivot Tables** — Sales aggregation by region and product category.
- **Data Visualization** — Bar charts, line charts, and pie charts.
- **Conditional Formatting** — Highlighting important customer records and values.

## 📂 Workbook Structure

The Excel workbook contains the following eight worksheets:

| Worksheet | Description |
|---|---|
| `Dashboard & Summary` | Executive KPI dashboard, project summary, and refresh timestamp. |
| `Dataset` | Main dataset containing 200 sales records and nine fields. |
| `Top Customers` | Customer purchase totals with conditional formatting. |
| `What-If Analysis` | Estimates the effect of discount adjustments on total profit. |
| `Stats & Regression` | Descriptive statistics and regression analysis of profit versus sales. |
| `Monthly Growth` | Monthly sales totals, month-over-month growth, and trend arrows. |
| `High Value Customers` | Customer purchase, profit, region, and quantity analysis using lookup formulas. |
| `Pivot Table` | Aggregated sales across regions and product categories. |

## 📋 Dataset Description

The `Dataset` worksheet contains the following fields:

| Column | Description |
|---|---|
| `Customer_ID` | Unique customer identifier used in the dataset. |
| `Customer_Name` | Name associated with the sales record. |
| `Region` | Geographic region of the transaction. |
| `Product_Category` | Category of the product sold. |
| `Sales` | Sales revenue for the record. |
| `Quantity` | Number of units sold. |
| `Discount` | Discount applied to the transaction. |
| `Order_Date` | Date of the order. |
| `Profit` | Profit recorded for the transaction. |

**Dataset size:** 200 records and 9 columns.

**Analysis period:** April 2024 to April 2025.

**Product categories:** Books, Clothing, Electronics, Furniture, and Office Supplies.

**Regions:** Central, East, North, South, and West.

## 📈 Key Features & Analysis

### 1. Executive KPI Dashboard

The dashboard provides a centralized summary of business performance.

- Total revenue.
- Total profit.
- Total quantity sold.
- Dynamic refresh timestamp using `NOW()`.
- Project task execution summary.
- Charts and business insights for quick interpretation.

### 2. Top 10 Customer Analysis

Identifies high-purchasing customers based on sales totals.

- Customer-level purchase analysis.
- Ranking of customer purchases.
- Conditional formatting to emphasize important values.
- Support for customer prioritization and retention decisions.

### 3. Discount What-If Analysis

Evaluates hypothetical discount changes and their estimated impact on total profit.

The workbook models five scenarios:

- 10% reduction in discount.
- 5% reduction in discount.
- Current discount level (baseline).
- 5% increase in discount.
- 10% increase in discount.

The scenarios use a simplified calculation based on total sales and an assumed 35% adjustment factor. These are **estimates rather than forecasts from a validated pricing model**.

### 4. Descriptive Statistics

Calculates important statistical measures for sales, profit, quantity, and discount.

- Mean.
- Standard deviation.
- Minimum.
- Median.
- Maximum.
- Count.

These metrics help summarize the distribution and variability of the data.

### 5. Linear Regression Analysis

Examines the relationship between sales and profit.

The workbook reports the following regression results:

| Metric | Recorded Value |
|---|---:|
| R-squared (R²) | 0.598 |
| Slope coefficient | 0.3509 |
| Intercept | -1.0316 |
| F-statistic | 294.7 |

The recorded R-squared indicates that approximately 59.8% of the variation in profit is explained by sales in the fitted model.

The slope represents the estimated relationship between sales and profit, not proof that increasing sales alone will cause profit to rise by a fixed amount.

### 6. Monthly Sales Growth

Analyzes sales performance over time using monthly totals.

- Monthly sales aggregation.
- Month-over-month growth calculations.
- Upward and downward trend arrows.
- Identification of stronger and weaker sales months.
- Support for trend analysis and performance monitoring.

### 7. High-Value Customer Analysis

Examines customer records using lookup and aggregation logic.

- Customer ID and name.
- Region.
- Total purchase value.
- Total profit.
- Total quantity.
- INDEX and MATCH lookup functions.

This worksheet helps identify customer records that may deserve closer business attention.

### 8. Regional & Product Category Analysis

Uses a pivot-style summary to compare sales across five regions and five product categories.

- Regional sales comparisons.
- Category-level sales analysis.
- Grand totals by region and category.
- Identification of stronger and weaker market segments.

## 🧮 Excel Functions Used

| Function | Purpose |
|---|---|
| `SUM()` | Calculates total sales, profit, and quantity. |
| `AVERAGE()` | Calculates average metric values. |
| `STDEV.S()` | Measures sample standard deviation. |
| `MEDIAN()` | Finds the middle value. |
| `MIN()` and `MAX()` | Identify minimum and maximum values. |
| `COUNT()` | Counts numeric observations. |
| `IF()` | Determines monthly trend indicators. |
| `INDEX()` | Returns a value from a specified range. |
| `MATCH()` | Locates a matching position in a range. |
| `NOW()` | Displays a dynamic date and time. |

Additional techniques include conditional formatting, lookup-based analysis, regression statistics, and pivot-style reporting.

## 💡 Business Value

This project demonstrates how spreadsheet analytics can support practical business questions:

- Which customers contribute the most sales?
- How do sales and profit vary across regions?
- Which product categories generate stronger sales?
- How do monthly sales change over time?
- What relationship exists between sales and profit?
- How might different discount scenarios affect estimated profitability?
- Which performance indicators should decision-makers monitor?

The analysis provides a foundation for customer segmentation, sales monitoring, pricing discussions, and performance reporting.

## 🚀 How to Use the Project

1. Download or clone this repository.
2. Open `2. Analyzer_Project.xlsx` in Microsoft Excel.
3. Navigate to `Dashboard & Summary` for the overall project overview.
4. Open `Dataset` to inspect the underlying sales records.
5. Explore the individual analysis worksheets to review the calculations.
6. Check the regression, monthly growth, and pivot-table results.
7. Update the dataset if required and verify that formulas, summaries, and charts reflect the new records.

**Note:** Some formulas, particularly `NOW()`, recalculate when the workbook is opened or recalculated. Ensure Excel calculation settings are enabled and review formulas when adding new records.

## ⚠️ Assumptions & Limitations

- The workbook uses the supplied dataset; the records should not be interpreted as verified real-world company transactions.
- The discount what-if scenarios use a simplified assumed adjustment factor and do not account for all pricing, demand, or cost effects.
- Regression results describe the relationship observed in the analyzed data and do not establish causation.
- The workbook's formulas and summaries should be checked when the dataset structure changes.
- Customer names and IDs are analyzed as provided in the workbook; repeated names or IDs may represent separate records and should be validated before drawing unique-customer conclusions.

## 🔮 Future Improvements

- Add interactive slicers and filters to the dashboard.
- Introduce revenue, profit-margin, and average-order-value KPIs.
- Improve data validation and automated data cleaning.
- Build a more robust discount and profitability model.
- Add customer segmentation based on purchasing behavior.
- Create a Power BI dashboard using the same dataset.
- Automate data refresh and reporting workflows.

## 📚 Skills Demonstrated

- Microsoft Excel and spreadsheet modeling.
- Data cleaning and dataset organization.
- KPI development and dashboard reporting.
- Statistical analysis and linear regression.
- Customer and sales performance analysis.
- Formula-based automation and lookup functions.
- Conditional formatting and data visualization.
- Business insight generation and analytical storytelling.

## 👨‍💻 Author

**Prince Rabari**

Aspiring data analyst interested in data analytics, business intelligence, and transforming raw data into actionable insights.

---

⭐ **If you find this project useful, consider giving the repository a star.**

*This project was developed for learning, analytical practice, and demonstrating practical Excel data analysis skills.*

# Screenshots of the project is given below:

<img width="1366" height="768" alt="Screenshot (271)" src="https://github.com/user-attachments/assets/b25b45c9-cc5b-4f2d-ac45-8e5db2641234" />
<img width="1366" height="768" alt="Screenshot (272)" src="https://github.com/user-attachments/assets/f585c1bf-3381-408c-8688-ffd27b0e5e6f" />
<img width="1366" height="768" alt="Screenshot (275)" src="https://github.com/user-attachments/assets/cbb0a5c5-38d4-42f2-886c-645a79431caf" />
<img width="1366" height="768" alt="Screenshot (276)" src="https://github.com/user-attachments/assets/7a470c25-46a3-4ce9-bb06-62e45ac03636" />
<img width="1366" height="768" alt="Screenshot (277)" src="https://github.com/user-attachments/assets/91145d65-a4cc-4d8f-b8d1-997b4da083d1" />
