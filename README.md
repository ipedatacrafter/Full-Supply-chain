Supply Chain Analytics Dashboard

An interactive Power BI dashboard for analyzing sales, inventory, supplier, and transportation performance across product categories — built to support supply chain planning and operational decision-making.

Overview

This project brings together sales, inventory, supplier, and logistics data into a single, filterable reporting tool. It is organized into three linked pages, each targeting a different part of the supply chain: demand-side performance, supplier/inventory performance, and operational/transportation efficiency.

Tools used: Power BI · SQL · Excel · Data Modeling

Dashboard Pages
1. Sales Analysis

Tracks revenue and product performance across product types (skincare, haircare, cosmetics) and customer demographics.

Revenue generated, product variants, units sold, and average availability at a glance (KPI cards)
Revenue breakdown by product type (donut chart)
Availability by product type (bar chart)
Revenue by customer demographics and product type (stacked bar chart)
Units sold by product type (bar chart)
SKU-level detail table with revenue and units sold, filterable by customer demographics and product type
<img width="909" height="510" alt="image" src="https://github.com/user-attachments/assets/d0bca1c5-5b2a-44f8-829f-beda5d4c7d4d" />


2. Inventory & Supplier Analysis

Evaluates supplier performance, shipping costs, and order fulfillment across locations.

Shipping cost and average shipping-time KPIs
Shipping cost by location and supplier (matrix table)
Order quantities by SKU (bar chart)
Order quantities by supplier and product type (donut and stacked bar charts)
Shipping costs by carrier and supplier (stacked bar chart)
Filterable by product type, supplier name, and location

<img width="901" height="509" alt="image" src="https://github.com/user-attachments/assets/166a4fbd-835b-44c8-9283-1104ac204074" />


3. Operational Efficiency & Transportation

Analyzes manufacturing cost, route efficiency, product quality, and lead times.

Manufacturing cost and profit KPIs
Route efficiency by route (A/B/C)
Cost by transportation mode (road, rail, air, sea)
Defect rates by product type
Average lead time by supplier
Cost by supplier and product type, and by route/transportation mode
Filterable by product type

<img width="901" height="512" alt="image" src="https://github.com/user-attachments/assets/9e53cfa9-8dfa-4dbf-b17d-7ad372dffc12" />


Key Features
Multi-page Power BI report with cross-page filtering (product type, supplier, location)
KPI cards for at-a-glance metrics on each page
Mix of visual types (donut, bar, stacked bar, matrix table) chosen to match the analysis — composition, comparison, and ranking
SQL-based data modeling to structure sales, inventory, supplier, and logistics data for reporting
Data

The dataset covers product-level sales, inventory availability, supplier shipping performance, and transportation/logistics costs across multiple SKUs, suppliers, locations, and transportation modes.

How to Use
Open the .pbix file in Power BI Desktop.
Use the slicers on each page (Product Type, Supplier Name, Location) to filter the view.
Navigate between pages using the arrow controls at the top of the report.

Author: Mehrab Atik Contact: mehrabatik1234@gmail.com | LinkedIn
