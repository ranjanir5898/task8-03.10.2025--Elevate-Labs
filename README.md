# task8-03.10.2025--Elevate-Labs
TASK 8: Simple Sales Dashboard Design
# Superstore Sales Analysis Using Python and Power BI

## Project Overview
This project involved cleaning and preparing a Superstore sales dataset using Python and then creating an interactive sales dashboard with Power BI. The goal was to analyze sales performance across time, regions, and product categories to derive actionable business insights.

## What Was Done

### Data Cleaning (Python)
- Loaded the raw Superstore dataset (~10,000 rows, 21 columns).
- Handled missing values by filling Postal Code missing entries with 0 and dropping rows missing critical IDs like Order ID and Customer ID.
- Removed duplicate records.
- Converted date columns (Order Date, Ship Date) to datetime format.
- Standardized text columns by trimming leading and trailing spaces.
- Dropped unnecessary columns such as Row ID.
- Reset the dataframe index after cleaning.
- Exported the cleaned dataset as `SuperstoreCleaned.csv` for Power BI use.

### Dashboard Development (Power BI)
- Imported the cleaned dataset into Power BI Desktop.
- Created key visuals:
  - Line chart showing sales trends over months.
  - Bar chart comparing sales by region, with conditional color formatting to highlight performance.
  - Donut chart depicting sales distribution by product category (Technology, Furniture, Office Supplies).
- Added slicers for month-year, region and category.
- Applied conditional formatting to highlight top and bottom-performing regions.

## Key Insights
- The West region outperformed others consistently, especially in Q3.
- Technology category contributed the largest revenue share (36.4%).
- Sales peaked in months March, May, September, and November, with strong holiday season demand at year-end.

## Conclusion
Python was used for robust data cleaning and preparation, ensuring accuracy and completeness. Power BI enabled the creation of an interactive, visually effective dashboard that supports business decision-making by revealing regional and temporal sales patterns.

This workflow demonstrates the synergy of Python and Power BI for data analytics and visualization in sales performance analysis.
