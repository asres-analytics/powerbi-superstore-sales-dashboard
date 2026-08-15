# Dashboard Requirements

## Project Title

Power BI Superstore Sales Dashboard

---

## Objective

Develop an interactive and professional sales dashboard that provides insights into sales performance, profitability, customer behavior, and product performance using the Superstore Sales Dataset.

---

## Business Questions

The dashboard should answer the following questions:

### Sales Performance

- What is the total sales revenue?
- How have sales changed over time?
- Which regions generate the highest sales?
- Which categories contribute most to revenue?

### Profitability

- What is the total profit?
- Which categories are most profitable?
- Which regions generate the highest profit?
- How do discounts impact profitability?

### Product Performance

- What are the top-performing products?
- Which products generate the highest profit?
- Which products underperform?

### Customer Analysis

- Which customer segments generate the most revenue?
- Who are the top customers?
- How are customers distributed across regions?

---

## Dashboard Pages

### Page 1: Executive Overview

KPIs:

- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold
- Profit Margin %

Visuals:

- Sales Trend
- Profit Trend
- Sales by Category
- Sales by Region

---

### Page 2: Sales Analysis

Visuals:

- Monthly Sales Trend
- Yearly Sales Trend
- Sales by Region
- Sales by Market

Filters:

- Date
- Region
- Category

---

### Page 3: Product Analysis

Visuals:

- Top 10 Products by Sales
- Top 10 Products by Profit
- Sales by Category
- Sales by Sub-Category

Filters:

- Product
- Category
- Region

---

### Page 4: Customer Analysis

Visuals:

- Sales by Customer Segment
- Top Customers
- Customer Distribution

Filters:

- Segment
- Region
- Date

---

## Data Cleaning Tasks

Performed using Power Query:

- Verify data types
- Check for missing values
- Remove duplicate records
- Format date columns
- Rename columns where necessary

---

## Required DAX Measures

```DAX
Total Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Total Orders =
DISTINCTCOUNT(Orders[Order ID])

Total Quantity =
SUM(Orders[Quantity])

Profit Margin =
DIVIDE([Total Profit],[Total Sales],0)

Average Order Value =
DIVIDE([Total Sales],[Total Orders],0)
```

---

## Success Criteria

- Clean and professional design
- Interactive slicers and filters
- Fast performance
- Easy-to-understand KPIs
- Actionable business insights
- Mobile-friendly layout where possible

---

## Deliverables

- Power BI Dashboard (.pbix)
- Dashboard Screenshots
- Project Documentation
- GitHub Repository