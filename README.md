# Job Market Analytics Dashboard 2023

An end-to-end data analytics project analyzing over 32,000 job postings to help job seekers make data-driven career decisions. The project uses Excel Power Query for data cleaning and Power BI for interactive visualization.

## Dataset Source

Dataset sourced from Luke Barousse's Excel Data Analytics Course repository.
Repository: https://github.com/lukebarousse/Excel_Data_Analytics_Course/tree/main

## Business Questions Answered

- Which job roles offer the highest average salaries?
- Do remote jobs pay more than onsite roles?
- Which countries have the highest job demand?
- Which skills are most in demand across all roles?
- Does degree requirement affect salary levels?
- How did job postings trend across 2023?

## Data Pipeline

```text
Raw CSV
   │
   ▼
Power Query Cleaning
   │
   ▼
Star Schema Model
   │
   ▼
DAX Measures
   │
   ▼
Power BI Dashboard
```

## Dashboard Features

- Interactive slicers for Role, Country, Date Range, and Job Type
- Cross-filtering across all visuals
- Dynamic chart highlighting that automatically emphasizes the top value
- Dynamic dashboard title that updates with slicer selections
- Quarterly job posting trend analysis
- Top 10 skills analysis with relationships across tables
- Remote vs onsite salary and distribution comparison
- Role demand vs salary comparison chart

## Tools and Technologies

| Tool | Purpose |
|------|---------|
| Excel Power Query | Data cleaning and transformation |
| Power Pivot | Data modeling and relationships |
| DAX | Calculated measures and KPIs |
| Power BI Desktop | Interactive dashboard |

## Project Highlights

- Cleaned and transformed 32,000+ job records using Power Query.
- Built a star schema data model with optimized relationships.
- Created dynamic DAX measures for salary, demand, and trend analysis.
- Designed an interactive Power BI dashboard with cross-filtering and dynamic visuals.
- Delivered insights into salary trends, skill demand, remote work, and global hiring patterns.

