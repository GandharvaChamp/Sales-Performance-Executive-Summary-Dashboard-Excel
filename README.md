# Sales-Performance-Executive-Summary-Dashboard-Excel

An interactive Excel dashboard designed to analyze sales performance, revenue distribution, and profitability across multiple business dimensions.

This project transforms raw sales data into an executive-level reporting solution using Microsoft Excel, Power Query, PivotTables, PivotCharts, Slicers, and Filled Map visualizations.

The dashboard enables users to monitor key performance indicators (KPIs), explore sales trends, compare geographical performance, and evaluate revenue contribution across product categories and sales channels.

📊 Dashboard Preview


<img width="1041" height="607" alt="Screenshot 2026-11-02 145700" src="https://github.com/user-attachments/assets/9d02a23d-2c93-490a-828f-18fc2e76dfcd" />



🎯 Project Overview

Business Problem

Businesses generate large volumes of sales data across different products, countries, regions, and sales channels. However, raw transactional data alone does not provide an efficient way for decision-makers to monitor performance or identify important business trends.

The objective of this project was to develop an interactive executive summary dashboard that consolidates key sales metrics into a single reporting interface.

The dashboard addresses the following business questions:

How much revenue and gross profit is the business generating?

How does revenue change over time?

Which countries contribute the most and least revenue?

Which product categories generate the highest revenue?

How is revenue distributed across sales channels?

How do different geographical regions perform?

How does business performance change when a specific product category is selected?

Project Objectives

Develop an interactive executive summary dashboard using Microsoft Excel.

Prepare and transform raw sales data using Power Query.

Summarize business metrics using PivotTables.

Visualize revenue, profitability, and sales performance.

Implement interactive filtering across dashboard components.

Translate sales data into meaningful business insights and potential recommendations.

📁 Dataset Description

Source: Kaggle

The dataset contains 2,708 rows of sales records and includes information about orders, products, customers, geographical regions, and financial performance.

Dataset Attributes

Category

Attributes

Order Information

ID, Order Date

Time Dimensions

Year, Quarter, Month, Month Name, MonthNo, Year2, Quarter2, Month2

Geography

Region, Country

Customer Information

Customer Type

Sales Information

Sales Channel, Product Category, Product

Sales Metrics

Units Sold, Unit Price, Discount %

Financial Metrics

Revenue, COGS, Gross Profit, Gross Margin %

Cost Information

Unit Cost

The dataset provides multiple dimensions for analyzing sales performance and profitability.

🛠️ Tools & Technologies

Tool / Feature

Application

Microsoft Excel

Dashboard development and business analysis

Power Query

Data preparation and transformation

PivotTables

Data aggregation and KPI analysis

PivotCharts

Interactive data visualization

Excel Slicers

Dynamic product category filtering

Report Connections

Synchronizing slicers across multiple PivotTables

Excel Filled Maps

Geographical revenue analysis

Excel Hyperlinks

Dashboard navigation

🔄 Data Preparation & Transformation

The raw dataset was imported into Microsoft Excel and maintained in a separate raw data worksheet.

Power Query was used to prepare the data for analysis.

Data Preparation Steps

Imported the Kaggle sales dataset into Excel.

Inspected the dataset structure and available attributes.

Used Power Query for data preparation and transformation.

Extracted month and year attributes from the order date to support time-based analysis.

Reviewed and adjusted data types for relevant columns.

Applied appropriate Indian Rupee currency formatting to financial values.

Prepared the transformed data for PivotTable-based analysis.

The dataset required relatively limited cleaning, so the primary focus was on preparing the data for analytical reporting rather than extensive data correction.

📐 Key Performance Indicators (KPIs)

The executive summary presents the following key business metrics:

KPI

Description

Total Revenue

Total sales revenue generated

Total Gross Profit

Revenue remaining after deducting COGS

Gross Profit Margin

Gross profit expressed as a percentage of revenue

Total Units Sold

Total quantity of products sold

Total Orders

Number of recorded orders

COGS

Total cost of goods sold

KPI Calculations

The financial metrics are based on the following business definitions:

Revenue

Total sales value generated from product sales.

Cost of Goods Sold (COGS)

Total cost associated with the products sold.

Gross Profit

Gross Profit = Revenue − COGS

Gross Profit Margin

Gross Profit Margin = (Gross Profit / Revenue) × 100

These metrics provide an overview of business performance and profitability.

📈 Dashboard Features

1. Revenue & Gross Profit Trend Analysis

A monthly trend visualization compares revenue and gross profit over time.

Key capabilities:

Analyze monthly revenue fluctuations.

Compare revenue against gross profit.

Identify seasonal patterns in sales performance.

Explore trends across different product categories.

This visualization supports time-based performance monitoring and helps identify periods that may require further investigation.

2. Top 5 Countries by Revenue

A horizontal bar chart ranks the top five countries based on revenue.

Key capabilities:

Identify high-performing geographical markets.

Compare revenue contribution across countries.

Understand differences in market performance.

This analysis helps businesses evaluate geographical sales distribution.

3. Revenue Share by Sales Channel

A donut chart visualizes revenue contribution across different sales channels.

The dashboard includes:

Corporate

Marketplace

Online Store

Retail Partners

This visualization supports channel performance comparison and helps identify the channels contributing significantly to overall revenue.

4. Region-wise Revenue Analysis

A donut chart compares revenue distribution across geographical regions.

The dashboard includes:

Central Europe

Northern Europe

Southern Europe

Western Europe

This provides a consolidated view of geographical revenue contribution.

5. Country-wise Revenue Distribution

An Excel Filled Map visualizes revenue distribution geographically.

Key capabilities:

Explore revenue contribution across countries.

Identify geographical differences in sales performance.

Complement the country ranking chart with a spatial representation.

6. Interactive Product Category Slicer

The dashboard includes an interactive product category slicer.

Available categories:

Camping

Cycling

Fitness

Hiking

Travel

The slicer is connected to the dashboard's PivotTables through Report Connections.

Selecting a product category dynamically updates the connected dashboard components, allowing users to analyze performance at an individual category level.

7. Dashboard Navigation

Hyperlinks are implemented through navigation buttons in the dashboard header.

These provide a convenient way to navigate between relevant workbook sections.

#Key Business Insights

The following observations were identified through the dashboard analysis.

Geographical Performance

Germany is the highest-revenue country in the analyzed dataset.

Austria is the lowest-revenue country in the analyzed dataset.

These findings highlight differences in geographical sales performance.

Product Category Analysis

The Cycling category demonstrates variation in monthly revenue.

July is the highest-revenue month for Cycling.

February is the lowest-revenue month for Cycling.

This indicates a potential seasonal pattern in Cycling sales that could be investigated further.

Sales Channel Performance

Online Store contributes approximately 40% of total revenue.

Online Store is the highest-contributing sales channel.

Marketplace is the second-highest-contributing sales channel.

This highlights the importance of online sales channels in the revenue distribution.

💡 Potential Business Recommendations

Based on the observed patterns, the following recommendations could be explored.

1. Investigate Geographical Performance

Germany's strong revenue contribution could be analyzed further to understand the factors behind its performance.

Potential areas of investigation:

Product demand

Customer purchasing behavior

Sales channel distribution

Product category performance

Austria's comparatively lower revenue could also be investigated to identify potential growth opportunities.

2. Evaluate Seasonal Demand

The difference between July and February revenue in the Cycling category suggests a potential seasonal trend.

Businesses could investigate whether this pattern is associated with:

Seasonal customer demand

Product availability

Promotional campaigns

Regional purchasing behavior

Further analysis could help support inventory planning and marketing decisions.

3. Optimize Sales Channel Strategy

Since Online Store contributes approximately 40% of revenue, businesses could evaluate its performance in greater detail.

Potential actions include:

Analyze revenue and gross profit by sales channel.

Evaluate customer purchasing behavior across channels.

Investigate the performance of Marketplace.

Identify opportunities to improve lower-contributing channels.

These recommendations are exploratory and would require additional analysis before implementation.


#How to Explore the Project

Clone or download this repository.

Open the Excel workbook in Microsoft Excel.

Navigate to the Executive Summary Dashboard.

Explore the displayed KPIs and visualizations.

Use the Product Category slicer to filter the dashboard.

Observe how the connected charts and KPIs respond to the selected category.

Explore the geographical revenue distribution and monthly trends.

For the best experience, use Microsoft Excel with the workbook's interactive PivotTables, charts, and slicers enabled.

#Key Learnings

Through this project, I strengthened my understanding of:

Data preparation using Power Query.

Date-based data transformation.

KPI development and business metric interpretation.

PivotTable-based data aggregation.

PivotChart-based dashboard development.

Interactive filtering using Excel Slicers.

Report Connections across multiple PivotTables.

Geographical data visualization using Filled Maps.

Executive dashboard design and business reporting.

Translating sales data into business insights.


⭐ If you like this project, consider giving the repository a star!
