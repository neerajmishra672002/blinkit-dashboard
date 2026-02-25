# blinkit-dashboard
Project Overview
This project features a comprehensive Sales Analysis Dashboard for Blinkit, India's leading last-minute delivery app. The dashboard provides a granular view of sales performance, customer satisfaction, and inventory distribution. It is designed to help stakeholders identify key growth drivers and optimize supply chain efficiency across various outlet types and locations.
Key Insights & Features
KPI Tracking: Real-time tracking of Total Sales ($1.2M), Average Sales per Transaction ($141), Total Items Sold (9K), and Customer Ratings (4/5).
Fat Content Analysis: Breakdown of sales by Low Fat vs. Regular products, highlighting consumer health preferences across different outlet tiers.
Item Type Performance: Identification of top-performing categories, with Fruits & Vegetables and Snack Foods leading the revenue stream ($0.18M each).Outlet Segmentation:
Size: Comparing sales across Medium, Small, and High-capacity outlets.
Location: Analysis of Tier 1, Tier 2, and Tier 3 cities.
Type: Performance comparison between Supermarkets and Grocery Stores.
Temporal Trends: An "Outlet Establishment" line chart showing growth trends from 2012 to 2022, peaking significantly in 2018.
Tech Stack
Data Visualization: Power BI 
Data Processing: DAX /  Excel 
Business Impact
By using this dashboard, management can:
Optimize Inventory: Allocate high-demand "Item Types" to specific outlet tiers.
Targeted Marketing: Develop campaigns for "Low Fat" products in regions showing high consumption.
Strategic Expansion: Focus on Tier 3 locations which currently show the highest sales volume ($472.13K).
How to Use this Repository
Download the .pbix (or appropriate file type) from the root folder.
Open with [Power BI Desktop].
Interact with the filters (Outlet Size, Location, Item Type) on the left sidebar to slice the data.
Challenges & Solutions
Building this dashboard involved overcoming several data hurdles to ensure accuracy and a smooth user experience:
1. Data Normalization & Cleaning
The Challenge: Inconsistent naming conventions for "Item Fat Content" (e.g., "LF," "low fat," and "Low Fat" all representing the same category).
The Solution: Used Power Query (M language) to perform a data transformation step, standardizing all variations into two clean categories: Low Fat and Regular.
2. Handling Multi-Tier Geographic Data
The Challenge: Visualizing the relationship between Tier 1, 2, and 3 cities without cluttering the main view.
The Solution: Implemented a Funnel Chart for "Outlet Location," which intuitively shows the distribution of sales volume across tiers, making it clear that Tier 3 is the primary revenue driver ($472.13K).
3. Calculating Comparative Metrics
The Challenge: Creating a single view that compares "Total Sales" against "Item Visibility" and "Average Rating" across different outlet types.
The Solution: Developed custom DAX measures to calculate weighted averages for ratings and visibility, then displayed them in a consolidated Matrix Table with conditional formatting (Heat Map) for instant visual cues on performance.
4. UI/UX Consistency
The Challenge: Fitting 8+ different visualizations into one screen without overwhelming the user.
The Solution: Applied a tiled layout with clear white-space separation and adopted the Blinkit brand guidelines (Yellow/Black/White). I used a left-hand navigation pane for slicers to maximize the "real estate" for the actual data charts.
screenshot



