# NYC School Construction Authority (NYCSCA) Dashboard

This Power BI dashboard analyzes active school construction projects across New York City to provide visibility into project distribution, funding, and geographic coverage.

The goal of this project is to transform raw project-level data into a clear, decision-support tool that highlights where investments are being made and identifies gaps in funding and project allocation.

---

## Overview

The dashboard provides an interactive view of NYCSCA projects currently under construction, enabling users to explore:

- Project distribution across boroughs and districts  
- Total construction investment (Prime Construction Award)  
- Projects with missing or incomplete funding data  
- Geographic clustering of school construction activity  

---

## Tools & Technologies

- Power BI (Data Modeling, DAX, Visualization)
- Power Query (Data Cleaning & Transformation)
- Excel (Source Data)
- Geospatial Mapping (Latitude/Longitude)

---

## Key KPIs

- Total Active Projects  
- Total Construction Award ($)  
- Average Award per Project  
- Projects Missing Award Data  
- Projects by Borough  
- Projects by District  

---

## Dashboard Features

- **Interactive Filters:** Borough, District, Project Type  
- **Geospatial Map:** Visualizes project locations across NYC  
- **KPI Cards:** High-level summary metrics for quick insights  
- **Breakdown Visuals:** Distribution of projects by borough and district  
- **Data Quality Tracking:** Highlights missing award values  

---

## Key Insights

- Manhattan and Brooklyn show the highest concentration of active construction projects  
- Some projects are missing award values, indicating potential data quality gaps  
- Investment is unevenly distributed across districts, with some areas receiving significantly higher funding  
- Geographic visualization helps identify clusters of development and underserved regions  

---

## Data Notes

- Source: NYC School Construction Authority (NYCSCA) Active Projects dataset (https://data.cityofnewyork.us/Housing-Development/Active-Projects-Under-Construction/8586-3zfm/about_data)
- "Construction Award" represents the value of the prime construction contract  
- Some records contain missing values for award amount or geographic coordinates  
- Data was cleaned and standardized in Power Query before analysis  

---

## Files

- `NYCSCA Active Projects Under Construction Final.pbix` – Main Power BI dashboard  
- `screenshots/` – Dashboard previews  

---

## How to Use

1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use slicers to filter by borough, district, or project type  
4. Explore KPIs and map to understand project distribution  

---

## Project Goal

This project demonstrates how operational public-sector data can be structured into a scalable reporting framework. It focuses on:

- Defining clear KPIs from raw data  
- Building a reusable reporting structure  
- Highlighting data quality issues alongside insights  
- Delivering a dashboard that supports planning and decision-making  

---

## Future Improvements

- Add time-based analysis (project timelines, trends)  
- Integrate additional datasets (budget vs. actuals, completion status)  
- Enhance data validation rules for missing fields  
- Optimize DAX measures for scalability  

---

## Author

Deepta Raghavan  
