## Title: Global Economic Indicators Dashboard (Power BI)
## Project Overview
This Power BI dashboard analyzes global economic and population data sourced from the World Bank’s public API. It allows users to explore macroeconomic indicators such as GDP, GDP per capita, GDP growth rate, and population density across various countries and regions.

The goal is to help analysts, policymakers, and researchers gain insights into global economic performance trends over time and across geographical areas.
## Key Features
### Page 1: Overview Dashboard
•	Line Chart: Global GDP Annual Growth % over the years.
•	Choropleth Map: Regional GDP distribution by country (color-coded by region).
•	Bar Chart: Top countries by GDP, segmented by region.
•	KPI Table: Displays 2020 data – Country name, GDP, Population, GDP per capita, and Population Density with conditional formatting.

### Page 2: Country Drillthrough (Example: Russian Federation)
•	Dynamic page accessed via drill-through for country-specific analysis.
•	Key metrics at a glance: Population, GDP, GDP per capita, Population Density.
•	Dual-axis Combo Chart showing:
o	GDP Annual Growth % (bars)
o	Total GDP (line)
•	Tabular data with year-wise breakdown of GDP, population, and per capita values.
### Page 3: Metadata
•	Provides clear documentation of:
o	Data sources (World Bank APIs)
o	Indicator definitions and aggregation methods
o	License details and metadata comments
## Technical Stack
•	Tool: Microsoft Power BI
•	Data Source:
o	World Bank Open API
o	Endpoints used:
	Population: SP.POP.TOTL
	GDP (constant 2015 US$): NY.GDP.MKTP.KD
	GDP per capita: NY.GDP.PCAP.KD
•	Data Processing:
o	Power Query Editor used to transform JSON API data
o	Data model created using relationships among metrics
•	Visuals Used:
o	Line Chart, Bar Chart, Map (Choropleth), KPI Cards, Combo Chart, Table
•	Interactivity:
o	Drill-through navigation
o	Conditional formatting
o	Region-wise filtering
Conclusion
This Power BI project showcases the ability to build an interactive and insightful data analytics dashboard using real-time, publicly available API data. It demonstrates key Power BI skills, including data extraction from APIs, transformation, modeling, visual design, and storytelling.
The dashboard enables users to:
•	Monitor global economic trends.
•	Compare countries and regions based on economic strength.
•	Explore data in a self-service manner via drill-through and interactivity.

