# Coffee Sales Interactive Dashboard (Excel)

## Overview
This project showcases an interactive Excel dashboard built to analyze coffee shop sales performance across time, products, customers, and regions. The dashboard enables users to explore sales trends and customer behavior through dynamic filters and visualizations.


<img width="1461" height="821" alt="image" src="https://github.com/user-attachments/assets/606c2870-1d3d-46bd-a284-f1f23c5ab452" />

## Data Sources

Customers table / Products table / Orders table

## Data Preparation & Transformation

- Joined customer and product information into the orders dataset using **XLOOKUP** and **INDEX-MATCH**

- Created a calculated **Sales** column based on order quantity and unit price

- Used **IF** statements to standardize full coffee brand names from abbreviated product codes

- Cleaned and formatted data, including removing duplicates and ensuring consistent data types

## Analysis & Visualization

Built multiple **PivotTables** to analyze:
- Sales trends over time
- Revenue by country and region
- Customer purchasing behavior
- Product size and roast type performance
- Created PivotCharts for revenue trends, regional sales, and top customers

## Dashboard Features

- Fully interactive dashboard with **slicers and timeline controls**

- Filters by:
  - Order date
  - Roast type (Dark, Medium, Light)
  - Product size
  - Country
  - Loyalty card status
  - Designed for intuitive exploration and quick business insights
