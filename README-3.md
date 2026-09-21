# ☕ Coffee Sales Analysis Dashboard

An interactive sales dashboard that breaks down coffee shop performance by month, location, time of day, product category, and product type.

![Dashboard preview](dashboard.jpg)

## Overview

This project analyzes transaction-level coffee sales data to answer questions like:

- How does revenue change month over month?
- Which store locations perform best?
- What hours of the day drive the most sales?
- Which product categories and product types generate the most revenue?

## Key Metrics (KPIs)

| Metric | Value |
|---|---|
| Total Revenue | 579,871.2 |
| Sum of Unit Price | 418,633.4 |
| Total Transaction Quantity | 178,001 |

## Dashboard Components

| Section | Chart Type | What It Shows |
|---|---|---|
| **Monthly** | 3D column chart | Revenue by month (January to June) |
| **Location** | Pie chart | Revenue split across Astoria, Hell's Kitchen, and Lower Manhattan |
| **Time** | Column chart | Revenue by hour of day (6 AM to 8 PM) |
| **Distribution of Product Category** | Line chart | Revenue across product categories |
| **Distribution of Product by Type** | Bar chart | Revenue by product type (syrups, beans, teas, chocolate, etc.) |

### Interactive Filters (Slicers)

- **Month**: filter the whole dashboard by month
- **Product Category**: filter by Bakery, Branded, Coffee, Coffee beans, Drinking Chocolate, and more

## Key Insights

- **Revenue is growing:** Monthly revenue rises from about 81.7K in January to about 166.5K in June, with a sharp jump between March and May.
- **Locations are evenly balanced:** All three stores earn roughly 190K to 196K, with Lower Manhattan slightly ahead.
- **Mornings drive sales:** Revenue peaks around 10 AM (about 73.2K) and stays high from 8 AM to 10 AM, then settles into a steady plateau through the afternoon and drops off after 6 PM.
- **A few categories dominate:** One product category reaches about 224K in revenue, far above the rest.
- **Top product types:** Several types, such as Brewed Chai tea (about 63.8K), Barista Espresso-style items, and Brewed herbal tea, lead the product-type breakdown.

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers)
- Custom brown, coffee-inspired theme for the dashboard layout

## How to Use

1. Open the dashboard file in Excel.
2. Use the **month** and **product_category** slicers to filter the data.
3. Click the filter icon in a slicer to clear the selection.
4. Watch the KPIs and all charts update automatically.

## Project Structure

```
├── coffee_sales_dashboard.xlsx   # Dashboard and pivot tables
├── data/                         # Raw sales data
├── dashboard.jpg                 # Dashboard screenshot
└── README.md
```

## Data Fields

Fields used in this analysis include:

- `transaction_qty`
- `unit_price`
- `product_category`
- `product_type`
- `store_location`
- `month`
- `hour` (time of day)

## Future Improvements

- Add year-over-year and month-over-month growth metrics
- Add a profit or margin view
- Add a top 10 products ranking
- Publish the dashboard to Power BI or Tableau for web sharing

## Author

**Your Name**
[LinkedIn](#) · [GitHub](#)
