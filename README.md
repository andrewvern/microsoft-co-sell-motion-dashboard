### Microsoft Co-Sell Motion Dashboard
This dashboard was built as part of a senior capstone project using dummy/masked data. All values are simulated and do not represent real business information.

## Project Overview  
The Microsoft Co-Sell Motion Dashboard provides stakeholders with actionable insights by combining data from multiple partner, product, and regional dimensions. It surfaces performance trends, highlights key growth opportunities, and enables filtering across various business attributes. Originally developed as part of a group project, this version reflects my individual contribution—specifically, I was solely responsible for designing the data model, cleaning and preparing the dataset, and conducting all exploratory data analysis.

## Data Model

This Power BI project uses a snowflake schema with 3 fact tables and several dimensions to support workload and partner-level analysis.

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

## Features
Dynamic filtering by region, product, and partner tier

Ranking of top five partner solutions by scoring index

Visual breakdowns of engagement volume, pipeline size, and conversion metrics

Built-in data modeling to support drill-down analysis

Export-ready Power BI visuals for executive presentations

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


