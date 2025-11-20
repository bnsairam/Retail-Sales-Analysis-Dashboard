Retail Sales Analysis Dashboard

A fully interactive and visually appealing Excel dashboard designed to analyze retail sales performance, monitor business KPIs, and uncover actionable insights. This project demonstrates end-to-end data cleaning, preparation, and dynamic dashboard creation using Microsoft Excel.

Overview

This project presents a comprehensive Retail Sales Dashboard built using Excel Pivot Tables, Pivot Charts, Slicers, and KPI cards. It allows users to quickly understand business performance through:

Sales trends: Identify month-over-month or seasonal fluctuations

Category & product insights: Understand which products generate the most revenue

Regional analysis: Compare performance across different cities and states

Order patterns: Monitor quantity sold, order frequencies, and distribution

Key KPIs: Track Total Sales, Total Quantity, Total Orders, and other metrics

The dashboard is ideal for analysts, managers, and business owners who need fast and reliable performance insights without complex BI tools.

Dashboard Preview

Features

Sales Trend Charts: Visualize sales and quantity trends clearly over time

KPI Cards: Display key business metrics at a glance

Category Performance: Identify top-selling and underperforming categories

Geographical Breakdown: Understand how different cities and states contribute to total revenue

Discount Analysis: Evaluate how discounts affect total revenue

Interactive Slicers: Filter data by Month, Category, State, and Sales Channel

Clean UI: Professional design with clear color-coding and layout

Each element of the dashboard refreshes automatically when new data is added.

Repository Structure
Retail-Sales-Analysis-Dashboard/
│
├── ExcelDashboard.png              # Dashboard preview image
├── Retail_Sales_Dashboard.xlsx     # Main Excel dashboard file
├── sales_data.xlsx                 # Sample or raw dataset used
└── README.md                       # Documentation

Dataset Description

The dataset contains transactional retail sales information with the following fields:

Order ID: Unique order identifier

Order Date: Date of purchase

Category & Sub-Category: Product grouping

Quantity: Units sold

Unit Price: Price per item

Discount: Percentage or absolute discount applied

Revenue: Final bill amount

City & State: Delivery location

Sales Channel: Online, Offline, Marketplace, etc.

Data preparation includes:

Removing duplicates and blank rows

Cleaning spelling inconsistencies and category labels

Converting date fields to proper Excel date formats

Creating calculated fields (Revenue, Discounted Amount, Net Sales)

Changing column types for accuracy (dates, numbers, text)

This ensures accurate and error-free dashboard calculations.

Tools Used

Microsoft Excel — main tool for dashboard building

Pivot Tables — data summarization

Pivot Charts — visual representation

Slicers — filtering interactions

Power Query (optional) — for data import and cleaning

Power Pivot (optional) — for data modeling & DAX if needed

These tools together enable Excel to function as a lightweight BI solution.

How to Use
Clone the Repository
git clone https://github.com/bnsairam/Retail-Sales-Analysis-Dashboard.git

Navigate to Folder
cd Retail-Sales-Analysis-Dashboard

Open the Dashboard
start Retail_Sales_Dashboard.xlsx

(Optional) Add Your Own Dataset

Replace the sample dataset with your own:

copy "C:\YourData\sales_data.xlsx" ".\sales_data.xlsx"

Refresh Excel Data

Inside Excel:

Data → Refresh All


This reloads the Pivot Tables, charts, and KPIs with your updated data.

Insights (Example)

Below are sample insights you may find after analyzing the dataset:

Festive season contributes significantly to total annual sales, showing strong seasonal demand

Electronics and Fashion are the highest-revenue categories, driving majority of total sales

Metro cities generate the highest volume, showing strong urban customer base

Heavy discounts reduce revenue despite increasing quantity sold, indicating margin impact

Weekend orders show consistent spikes, useful for staffing & logistics planning

Replace these with your actual insights after analysis.

Future Enhancements

Add profit, margin, and cost analysis

Integrate forecasting to predict future sales based on historical trends

Build a Power BI version of the dashboard

Add automated PDF reporting using macros

Include customer segmentation based on demographics or buying behavior

These enhancements can make the dashboard more powerful and industry-ready.

Contributing

To contribute to this project:

git checkout -b feature-name
git add .
git commit -m "Added new feature"
git push origin feature-name


Pull requests are welcome.

Author

Sairam

GitHub:
https://github.com/bnsairam

Website:
https://bnsairam.vercel.app/

Email:
bnsairam14@gmail.com
