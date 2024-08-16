Power BI Dashboard: Sales Performance Analysis
Overview
This Power BI dashboard offers an in-depth analysis of sales performance, focusing on key metrics such as Total Cost, Total Quantity, and Customer Demographics. The dashboard allows users to explore data across various dimensions, including product categories, customer age groups, and geographic regions.

Key Features
Total Cost Analysis: Visualize total costs by year, month, and product category.
Customer Demographics: Analyze customer gender and age group distributions across different time periods.
Quantity Sold: Track the total quantity sold by customer gender and product categories over time.
Interactive Filters: Use slicers for product categories, subcategories, and countries to drill down into specific data segments.
Time Analysis: Analyze performance by year, month, and day with detailed date and calendar filters.
Unit Price Grouping: Group total costs by unit price categories to identify sales distribution across different price points.
Dashboard Elements
Top Row Visuals:

Total Cost by Year, Month, and Product Category: Line chart displaying cost trends over time across different product categories like Accessories, Bikes, and Clothing.
Total Customer Gender by Year, Month, and Age Group: Bar chart visualizing customer demographics, categorized by age groups and gender.
Total Quantity by Year, Month, and Customer Gender: Bar chart showing the total quantity sold over time, segmented by customer gender.
Middle Section:

Date & Calendar Filters: Slicers allowing users to filter data by Year, Month, and Day. Additional options to filter by Total Price, Total Cost, and Total Quantity.
Total Cost by Day and Unit Price Group: Stacked bar chart representing daily costs, broken down by unit price groups ranging from under 100 to over 2000.
Total Cost by Day and Age Group: Area chart showing daily cost trends segmented by different age groups (<25, 25-54, 55+).
Right Section:

Product Categories & Subcategories Slicer: A hierarchical slicer allowing users to select specific product categories (e.g., Accessories, Bikes, Clothing) and their subcategories.
Country Slicer: Slicer enabling users to filter data by geographic region, including the United Kingdom, France, United States, and Germany.
Data Sources
Sales Data: Comprehensive dataset including transaction details, product categories, customer demographics, and geographic information.
Time Dimension: Calendar table used to analyze data across different time periods.
Technical Details

DAX Measures: Custom measures created for calculating total costs, quantities, and segmenting data by unit price groups and age groups.
Data Model: Star schema employed with fact tables for sales data linked to dimension tables for products, customers, and time.
Usage Instructions
Clone the Repository:
bash

Open in Power BI Desktop: Load the .pbix file using Power BI Desktop.
Adjust Data Connections: Update data source connections as needed to match your environment.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your enhancements.

License
This project is licensed under the MIT License.
