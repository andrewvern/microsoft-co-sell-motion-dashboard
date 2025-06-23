Microsoft Co-Sell Motion Dashboard
This project delivers an interactive Power BI dashboard designed to visualize and track the performance of Microsoft Co-Sell motions, enabling sales and partnership teams to identify top-performing partner solutions, optimize engagement strategies, and drive revenue growth.

## Project Overview  
The Microsoft Co-Sell Motion Dashboard provides stakeholders with actionable insights by combining data from multiple partner, product, and regional dimensions. It surfaces performance trends, highlights key growth opportunities, and enables filtering across various business attributes.

## Features
Dynamic filtering by region, product, and partner tier

Ranking of top five partner solutions by scoring index

Visual breakdowns of engagement volume, pipeline size, and conversion metrics

Built-in data modeling to support drill-down analysis

Export-ready Power BI visuals for executive presentations

## Data Model

This Power BI project uses a star schema with 3 fact tables and several dimensions to support workload and partner-level analysis.

### Fact Tables
- `fact_CustomerWins`
- `fact_Workloads`
- `fact_PartnerScores`

### Dimension Tables
- `dim_partner2`
- `dim_customer2`
- `dim_activity2`
- `dim_solutionAreaMap2`
- `dim_partnerSolution2`
- `dim_partnerSolutionArea2`

![Data Model Diagram]
![ERD Data Model](https://github.com/user-attachments/assets/bea278f4-6737-4763-9b5c-89f029763d3e)


## Tech Stack
Power BI – for dashboard design and data visualization

SQL – for data extraction and transformation

Power Query (M) – for data cleaning and integration

Excel – for initial data inspection and prototyping

## Sample Views:

Solution Ranking
![image](https://github.com/user-attachments/assets/54d9a982-479e-4205-a298-ee593a7a2a5e)

Partner & Success Metrics
![image](https://github.com/user-attachments/assets/b2e7e69f-f168-4526-9600-a162a586b89b)

Solution
![image](https://github.com/user-attachments/assets/0b37206d-d91f-44a8-af42-373983400e2e)


