# Power BI Superstore Sales Dashboard

Interactive Sales Analytics Dashboard built with Microsoft Power BI using the Superstore Sales Dataset.

## Project Overview

This project analyzes sales performance, profitability, customer behavior, and product trends using the Superstore Sales Dataset.

The dashboard is designed to help business stakeholders:

- Monitor sales performance
- Track profitability
- Identify top-performing products
- Analyze customer segments
- Compare regional performance
- Discover business growth opportunities

## Dataset

Source: Kaggle

Dataset: [Superstore Sales Dataset](https://www.kaggle.com/datasets/aditisaxena20/superstore-sales-dataset)

## Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization

## Dashboard KPIs

### Sales Metrics

- Total Sales
- Total Orders
- Average Order Value
- Sales Growth %

### Profitability Metrics

- Total Profit
- Profit Margin %
- Profit by Category
- Profit by Region

### Customer Metrics

- Customer Segments
- Top Customers
- Customer Contribution

## Dashboard Pages

### 1. Executive Overview

Business summary and KPI cards:

- Total Sales
- Total Profit
- Total Orders
- Profit Margin

### 2. Sales Analysis

- Monthly Sales Trend
- Sales by Region
- Sales by Category
- Sales Growth Analysis

### 3. Product Analysis

- Top 10 Products
- Bottom 10 Products
- Sales by Category
- Sales by Sub-Category

### 4. Customer Analysis

- Customer Segmentation
- Top Customers
- Regional Customer Distribution

## Project Structure

```text
powerbi-superstore-sales-dashboard/
│
├── dashboard/
│   └── Superstore_Sales_Dashboard.pbix
│
├── data/
│   └── DATASET.md
│
├── docs/
│   └── dashboard-requirements.md
│
├── screenshots/
│   ├── customer-analysis.png
│   ├── executive-overview.png
│   ├── product-analysis.png
│   └── sales-analysis.png
│
├── .gitignore
├── LICENSE
└── README.md
```

## Data Preparation

Data cleaning and transformation performed using Power Query:

- Data type corrections
- Null value validation
- Data quality checks
- Date formatting
- Data modeling

## DAX Measures

Examples:

```DAX
Total Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Total Orders =
DISTINCTCOUNT(Orders[Order ID])

Profit Margin =
DIVIDE([Total Profit],[Total Sales],0)
```

## Screenshots

### Executive Overview

Coming Soon

### Sales Analysis

Coming Soon

### Product Analysis

Coming Soon

### Customer Analysis

Coming Soon

## Future Improvements

- Sales Forecasting
- Customer Lifetime Value Analysis
- RFM Analysis
- Advanced Profitability Analysis
- AI-Powered Insights

## Author

Asres Gamu Yelia

## License

This project is licensed under the MIT License. See the [LICENSE] file for details.

### Dataset License

This project uses the Superstore Sales Dataset available on Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/aditisaxena20/superstore-sales-dataset

The dataset remains the property of its original author and is subject to the licensing terms and conditions specified on Kaggle.

GitHub:
https://github.com/asres-analytics
