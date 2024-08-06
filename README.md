Retail Sales Forecasting Dashboard
Overview
This project involves creating a comprehensive Retail Sales Forecasting Dashboard using Power BI. The dashboard is designed to provide insights into sales performance, trends, and customer segmentation for a global superstore over a period of four years. The data has been analyzed and visualized to help stakeholders make informed decisions based on sales patterns and trends.

Dataset
The dataset used for this project is train.csv, which includes the following columns:

Row ID
Order ID
Order Date
Ship Date
Ship Mode
Customer ID
Customer Name
Segment
Country
City
State
Postal Code
Region
Product ID
Category
Sub-Category
Product Name
Sales
Project Steps
Data Preparation
Data Cleaning and Handling Missing Values

Verified and cleaned the dataset for any missing values. Columns with missing values were identified but not filled as part of this analysis.
Exploratory Data Analysis (EDA)

Performed analysis on sales trends, customer segments, and regional sales using Python (Jupyter Notebooks).
Feature Engineering

Created additional features for better analysis, including extracting Year and Month from the Order Date.
Power BI Dashboard
Setting Up Your Report Structure
Title and Introductory Text
Added a title and introductory text to provide context for the dashboard.
Title: "Retail Sales Dashboard"
Introductory Text: "This dashboard provides insights into sales performance, trends, and customer segmentation over the past four years for a global superstore."
Creating KPIs
Total Sales Card

Added a Card visualization to display the total sales amount.
Total Orders Card

Added a Card visualization to show the total number of orders.
Average Order Value Card

Added a Card visualization to display the average order value.
Top Performing Region Card

Created a measure to identify and display the region with the highest total sales.
Building Visualizations
Sales Trends Section

Monthly Sales Trends Line Chart
Added a Line Chart to show the sum of sales over time, with Order Date on the X-axis and Sales on the Y-axis.
Monthly Sales Trend Stacked Column Chart
Added a Stacked Column Chart to illustrate the breakdown of sales by category or sub-category over time.
Regional Performance Section

Sales by Region Clustered Bar Chart
Added a Clustered Bar Chart to display sales performance across different regions.
Sales Distribution by State Clustered Column Chart
Added a Clustered Column Chart to show sales distribution by state.
Product Analysis Section

Sales by Product Category Stacked Column Chart
Added a Stacked Column Chart to analyze sales by product category and sub-category.
Customer Segmentation Section

Sales by Customer Segment Donut Chart
Added a Donut Chart to display the distribution of sales by customer segment.
Sales by Ship Mode Donut Chart
Added a Donut Chart to show the distribution of sales by ship mode.
Sales by Category Donut Chart
Added a Donut Chart to illustrate sales distribution across different product categories.
Additional Visualizations

Monthly Sales Trend Area Chart
Added an Area Chart to show the trend of sales over months.
Sales by Sub-Category Tree Map
Added a Tree Map to visualize the breakdown of sales by sub-category (if needed).
Final Touches
Interactivity Enhancements

Although slicers were not included in this version of the dashboard, interactive features like bookmarks and tooltips can be added in future iterations to enhance user experience.
Review and Publish

Reviewed the dashboard to ensure accuracy and clarity.
Published the final report to Power BI Service for sharing with stakeholders.
Technologies Used
Python (Jupyter Notebooks): For data analysis and preprocessing.
Power BI: For creating the interactive dashboard and visualizations.
