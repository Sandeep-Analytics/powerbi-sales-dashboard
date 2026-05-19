# Power BI Sales Dashboard

## Overview
Interactive sales dashboard developed using Power BI to analyze revenue trends, regional performance, product sales, and payment insights.

## Tools Used
- Power BI
- Excel
- DAX

## Features
- KPI Cards
- Interactive Slicers
- Product Performance Analysis
- Monthly Sales Trend
- Regional Sales Insights
- Payment Mode Distribution

## Business Insights
- West region generated highest sales
- Speaker category achieved highest revenue
- Credit Card was the most preferred payment method

## Files Included
- Sales_Dashboard.pbix
- sales_data_100_records.xlsx
- dashboard.png

- ## DAX Measures Used

Total Revenue = SUM(Sheet1[Total_Sales])

Total Orders = COUNT(Sheet1[Order_ID])

Total Quantity = SUM(Sheet1[Quantity])

Average Sales = AVERAGE(Sheet1[Total_Sales])

Highest Sales = MAX(Sheet1[Total_Sales])

Lowest Sales = MIN(Sheet1[Total_Sales])

Total Customers = DISTINCTCOUNT(Sheet1[Customer_Name])
