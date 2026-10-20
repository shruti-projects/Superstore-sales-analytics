# Superstore Sales Analytics Dashboard

An interactive Power BI dashboard that analyses Superstore sales and profit from 2020 to 2023. The project covers the full analytics workflow: data preparation in Excel, data modelling and DAX measures in Power BI, and a one-page dashboard with insights and recommendations.

![Superstore Analytics Dashboard]([Screenshots/Superstore_Dashboard.pn](https://github.com/shruti-projects/Superstore-sales-analytics/blob/main/Superstore%20Sales%20Analytics/Screenshots/Superstore_Dashboard.png)
)

## Project Objective

To understand how sales and profit changed over time, which products, states and customer segments perform best, and how many orders are returned.

## Key Results

| Metric | Current | Previous Year | Change |
|---|---|---|---|
| Sales | $2.33M | $1.58M | +47.16% |
| Profit | $292.30K | $196.37K | +48.85% |
| Returned orders | 5.79% | 8.74% | -2.95% |

## Key Insights

- Sales grew 47.16% and profit grew 48.85% compared with the previous year.
- Monthly sales trend upward from 2020 to 2023, with the highest peak in late 2023.
- California and New York are the most profitable states; Texas is among the least profitable.
- Binders, Paper, Phones and Accessories give high profit, while Tables, Bookcases and Supplies give the lowest.
- 5.79% of orders were returned.

## Dashboard Features

- KPI cards for sales, profit and % of returned orders, each compared with the previous year
- Profit by Product (sub-category)
- Profit by state map
- Sales vs previous year over time
- Sales by Segment
- Slicers for customer name, country/region, segment and date

## Data Model

The model has four tables: **Orders**, **Returns**, **Date table** and **key measures**. The Date table connects to Orders on Order Date, and Returns connects to Orders on Order ID.


## Tools Used

- Microsoft Excel: data checking and cleaning
- Power BI Desktop: data modelling, DAX measures and dashboard
- DAX: previous-year comparisons and % of returned orders

## Dataset

Superstore sales data, covering 10,194 orders from January 2020 to December 2023. Source: [Sample Supermarket Dataset on Kaggle](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset)

## Repository Structure

```
Retail-Sales-Analytics/
├── Dataset/       Raw Superstore data
├── Excel/         Excel workbook used for checking and cleaning
├── PowerBI/       Power BI file (.pbix)
├── Screenshots/   Dashboard and data model images
├── Reports/       Written analysis report (PDF)
└── README.md
```

## Report

The full written analysis is in [Superstore Sales Analytics Report]([file:///C:/Superstore%20Sales%20Analytics/Reports/Superstore%20Sales%20Analytics%20Report.pdf](https://github.com/shruti-projects/Superstore-sales-analytics/blob/main/Superstore%20Sales%20Analytics/Reports/Superstore%20Sales%20Analytics%20Report.pdf)

## How to Open

1. Download or clone this repository.
2. Open the `.pbix` file in the `PowerBI` folder with Power BI Desktop.

## Author

Shruti Ambokar | shruti57107@gmail.com
