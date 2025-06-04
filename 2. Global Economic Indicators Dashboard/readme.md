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
    GDP Annual Growth % (bars)
    Total GDP (line)
•	Tabular data with year-wise breakdown of GDP, population, and per capita values.

### Page 3: Metadata
•	Provides clear documentation of:
    1. Data sources (World Bank APIs)
    2.  Indicator definitions and aggregation methods
    3. License details and metadata comments
## Technical Stack
•	Tool: Microsoft Power BI

•	Data Source:

    World Bank Open API
    Endpoints used:
            Population: SP.POP.TOTL
            GDP (constant 2015 US$): NY.GDP.MKTP.KD
           	GDP per capita: NY.GDP.PCAP.KD
•	Data Processing:
          	Power Query Editor used to transform JSON API data
            Data model created using relationships among metrics
•	Visuals Used:
            Line Chart, Bar Chart, Map (Choropleth), KPI Cards, Combo Chart, Table
•	Interactivity:  
            Drill-through navigation
            Conditional formatting
            Region-wise filtering

### Page 1:Dashboard
   ![image](https://github.com/user-attachments/assets/03ba7646-0c9a-4805-93eb-22e9511701e6)


### Page 2:Dashboard
   
![image](https://github.com/user-attachments/assets/b0bfbad5-3e9d-4d49-84d2-06d585b94164)


### Page 3:Dashboard

![image](https://github.com/user-attachments/assets/83b06097-0618-4c9c-8bad-e1d08fb405b5)


## Conclusion
This Power BI project showcases the ability to build an interactive and insightful data analytics dashboard using real-time, publicly available API data. It demonstrates key Power BI skills, including data extraction from APIs, transformation, modeling, visual design, and storytelling.
The dashboard enables users to:
•	Monitor global economic trends.
•	Compare countries and regions based on economic strength.
•	Explore data in a self-service manner via drill-through and interactivity.

