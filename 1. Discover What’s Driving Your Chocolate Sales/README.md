# Title of the Dashboard :Discover What's Driing Your Chocolate Sales

## Project Overview
Every chocolate box sold has a story about what people choose, when they buy it, where they live, and who sold it to them.

### In this project, I wanted to answer one key question:
### Which chocolates sell the most, in which places, and why?
We started with a large dataset containing sales records of products like Bubblegum Blitz and 50% Dark Bites. The data included details from different countries, salespeople, and dates. Our goal was to find hidden patterns in all this information.

## Features / Highlights
###  Business Problem
Sales managers lack a unified view of product performance, regional trends, and salesperson contributions. It's also difficult to track delivery consistency and product popularity at a glance.
### Goal of the Dashboard
To provide a centralized and user-friendly dashboard that:
Tracks chocolate sales volume and revenue across countries and time.
Identifies top and underperforming products and salespersons.
### Walkthrough of Key Visuals
we built an easy-to-use Power BI dashboard that turns raw data into useful insights.
 - **Line charts** showed how sales go up and down during certain times of the year, like during holidays.
 - **Bar  and donut charts** helped us see which chocolates are most popular and which countries bring in the most money.
 - **Tables** highlighted which salespeople sold the most, so we could recognize top performers or support others.
 - **KPI cards** gave a quick view of the total money made and the number of boxes sold.
 - **A calendar filter (slicer)** let users explore the data by year, quarter, month, or week.

## Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Core platform for developing interactive data visualizations.

🧹 Power Query – Used for data cleaning, transformation, and preparation.

🧠 DAX (Data Analysis Expressions) – Custom calculations and performance metrics like average sales per box, delivery rate, etc.

🧩 Data Modeling – Relationships among key data points (salesperson, product, date, country).

📁 File Format – .pbix for development and .xlsx as the input data source.

## Data Source
Source: Internal Sales Log (Excel file: sample-chocolate-sales-data-1.xlsx)

Structure:
Sales Person – Name of the person who made the sale
22 Products – Type of chocolate/candy product sold (e.g., White Choc,  50% Dark Bites)
Country – Country where the sale was made
Date – Transaction date
Amount – Total sale amount
Boxes – Number of boxes sold
Order Status – Delivery outcome (Delivered or Cancelled)

## Conclusion
As we worked through the data, the dashboard became more than just a report—it became a helpful tool for making smart decisions. It can now support planning, improve focus on best-selling products, and even help predict busy sales seasons.

## Dashbord Screenshort Page 2
  
![Chocolate Sales Performance Dashboard](https://github.com/user-attachments/assets/362ec4e0-cb39-4c16-a408-3b05f1a4859b)
## Dashbord Screenshort Page 1 with Saleperson tracker
![image](https://github.com/user-attachments/assets/7d58a0cd-9263-4387-a95e-a610d3a0e17b)
## Page 3 - sales Person Performance Rating by team wise

To provide a clear and insightful view of individual sales performance, I developed an interactive Power BI dashboard that compares each salesperson’s actual sales against a fixed target of $2,000,000. Utilized DAX formulas in Power BI, incorporating the CALCULATE and DIVIDE functions, as well as implementing IF and SWITCH conditional logic to enhance data analysis and drive dynamic insights. The dashboard features key performance metrics, target comparison, thumbs-up/down symbols, and star-based performance ratings for quick visual interpretation. An interactive slicer enables filtering by salesperson or team, offering flexibility and ease of use for business stakeholders to make informed decisions efficiently.
![image](https://github.com/user-attachments/assets/750583f2-bd14-4498-8742-d6ff501c51e4)
![image](https://github.com/user-attachments/assets/9508e3b0-f688-46fe-be19-7d56589313fb)
## Conclusion:
This Power BI report, “Discover What’s Driving Your Chocolate Sales,” explores what’s really helping drive chocolate sales across different products, teams, regions, and individual salespeople. With the help of clear visuals and calculated metrics, we were able to turn raw sales data into useful business insights.

Here’s what we found:

### Product Categories:
Chocolate products were grouped into Bars, Bites, and Other. We calculated the total sales for each group to understand which ones brought in the most revenue. This gives a clear idea of what customers prefer.

### Team and Region Performance:
The sales teams – Tempo, Delish, Juice, and Yummmies – were compared by how many boxes they sold and how much they earned across different regions.
We used line charts to show trends over time, and summary cards to show:

1. Total Sales

2. Total Boxes Sold

3. Shipment Count

### Salesperson Performance:
Each salesperson was rated based on whether they hit their sales targets. We also looked at their total sales by country. This helps understand who’s performing well and who might need support or recognition.

### Top-Selling Products:
We used a bar graph to highlight products that made over 1.5 million in sales. These are the clear winners that customers love and should be a focus for future sales strategies.

### Visual Insights:
With interactive visuals like slicers, trend lines, and summary cards, users can easily explore the data. Whether you're filtering by team, country, or category, the dashboard gives a quick and clear picture of what's happening.

In short, this analysis makes it easier to understand what’s working in your chocolate sales – from products and teams to individual performance. These insights can help drive smarter decisions in sales, marketing, and business planning.




