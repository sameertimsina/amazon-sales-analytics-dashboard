# E-commerce Sales Analytics Dashboard (Excel)

An Excel-based analytics project that turns 10,000 e-commerce sales records into an interactive KPI dashboard covering revenue, profit, product performance, and order outcomes.

## 1. Project Overview

This project analyzes e-commerce sales data using Microsoft Excel to evaluate business performance, understand sales and profitability patterns, and identify order fulfilment issues. Raw sales records are converted into KPIs, PivotTables, and interactive PivotCharts that a business stakeholder can use for monitoring and review.

**Dataset:** Sales dataset of 10,000 orders provided by my internship company for analytics training. The original source of the data is not specified, so the findings describe this dataset only and should not be treated as official Amazon performance.
**Period covered:** January 2024 to [last month in your data] 2026
**Records:** 10,000 orders

## 2. Business Problem

A sales team needs to know where revenue and profit come from, how healthy order fulfilment is, and where orders are lost to returns or cancellations.

Questions answered:

- How much revenue and profit does the business generate, and at what margin?
- What is the average value of an order?
- Which product categories and individual products drive sales and profit?
- How do sales and profit trend month by month?
- Which payment methods, fulfilment methods, and states contribute most?
- What share of orders are delivered, shipped, returned, or cancelled?

## 3. Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | ₹15,57,89,893.89 (~₹15.58 crore) |
| Total Profit | ₹3,31,67,008.49 (~₹3.32 crore) |
| Total Orders | 10,000 |
| Total Units Sold | 24,926 |
| Average Order Value | ₹15,578.99 |
| Overall Profit Margin | 21.29% |
| Return Rate | 4.85% |
| Cancellation Rate | 5.00% |

## 4. Key Findings

### Sales and profitability
- The business recorded about ₹15.58 crore in sales and ₹3.32 crore in profit, a 21.29% overall margin.
- **Electronics & Mobiles** generates the large majority of sales and profit, far ahead of Home & Kitchen, Apparel & Fashion, and Beauty & Personal Care. Pantry & Groceries contributes the least. [Add the exact share, e.g. "Electronics & Mobiles accounts for X% of total sales."]
- Units sold tell a different story from revenue: Electronics & Mobiles leads in units, followed by Apparel & Fashion, but Apparel sells many units at a much lower revenue per unit.
- The top-selling products by revenue are Laptop Backpack, Power Bank 20000mAh, 5G Smartphone, Wireless Earbuds, and Smartwatch. [Confirm the ranking against your pivot table.]

### Trend over time
- Monthly sales stay in a fairly steady range from 2024 through 2026, with no strong long-term growth or decline. [Add your peak month and its value if you want to highlight it. The chart shows a rise in mid-2026.]
- Monthly profit moves closely with sales and stays well below the sales line throughout the period.

### Order outcomes
Out of 10,000 orders:

| Order Status | Orders | Share |
|---|---:|---:|
| Delivered | 8,147 | 81.47% |
| Shipped | 868 | 8.68% |
| Cancelled | 500 | 5.00% |
| Returned | 485 | 4.85% |

*Return and cancellation rates use total orders as the denominator. Shipped orders are reported separately from delivered orders.*

### Payment, fulfilment, and geography
- **Payment method:** [Add the top method by sales and profit, with numbers.]
- **Fulfilment method:** [Add the comparison, with numbers.]
- **States:** [Add the top 3 states by sales, and whether the highest-selling state is also the most profitable.]
- **Returns and cancellations by category:** [Add the category with the highest returns or cancellations.]

## 5. Dashboard Preview

### Dashboard Overview
![Dashboard Overview](dashboard-overview.png)

### Sales and Profit Analysis
![Sales and Profit Analysis](dashboard-sales-analysis.png)

### Order Status and State-wise Analysis
![Order Status and State-wise Analysis](dashboard-orders-states.png)

## 6. Tools and Techniques

- **Microsoft Excel:** Data preparation, calculations, and dashboard layout
- **PivotTables and PivotCharts:** Summarizing and visualizing sales, profit, units, and order status by category, product, month, and state
- **Excel formulas:** KPI and percentage calculations (profit margin, average order value, return and cancellation rates)
- **Data cleaning and validation:** [List exactly what you checked or fixed, e.g. date formats, duplicates, blank values.]

## 7. Business Recommendations

- Protect and grow the Electronics & Mobiles category, since it drives most of the revenue, and review stock and pricing for its top products.
- Investigate why Pantry & Groceries contributes so little revenue despite non-trivial unit sales, and decide whether to reprice, bundle, or reduce the range.
- Look into the categories and states with the highest returns and cancellations to find out whether the cause is product quality, delivery, or listing accuracy. [Make this specific once you have the numbers.]
- Review the 8.68% of orders still in "Shipped" status to confirm they are in transit and not delayed.

## 8. Limitations

The findings are descriptive. They show where patterns exist but do not establish the causes of returns, cancellations, or differences in profitability. The dataset was provided for training purposes and its origin is unknown, so the results illustrate the analysis approach and should not be generalized to the real business.

## 9. Project Files

- `Amazon Sales Data India copy.xlsx`: Excel workbook with the data, PivotTables, and dashboard
- `dashboard-overview.png`, `dashboard-sales-analysis.png`, `dashboard-orders-states.png`: dashboard screenshots

## 10. Conclusion

This project shows how Excel can turn raw e-commerce sales data into a business-focused dashboard that combines KPI reporting, category and product analysis, trend tracking, and order-outcome monitoring to support data-informed decisions.
