# Job Market Analytics Dashboard 2023

## Project Overview

The Job Market Analytics Dashboard 2023 is an end-to-end data analytics project that analyzes over 32,000 job postings to identify trends in salaries, hiring demand, remote work, and required skills. The project uses Excel Power Query for data cleaning and transformation, Power Pivot for data modeling, DAX for calculations, and Power BI for dashboard development.

## Objectives

- Identify the highest-paying job roles.
- Compare salaries between remote and onsite positions.
- Analyze job demand across different countries.
- Identify the most in-demand skills.
- Examine the relationship between degree requirements and salary.
- Track hiring trends throughout 2023.

## Dataset

- **Source:** Luke Barousse's Excel Data Analytics Course Repository
- **Repository:** https://github.com/lukebarousse/Excel_Data_Analytics_Course/tree/main
- **Size:** Over 32,000 job postings from 2023

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Excel Power Query | Data cleaning and transformation |
| Power Pivot | Data modeling and relationships |
| DAX | Calculated measures and KPIs |
| Power BI Desktop | Interactive dashboard |

## Data Cleaning & Transformation

The dataset was prepared using Excel Power Query through the following steps:

- Removed duplicate records and handled missing values.
- Standardized job titles and location formats.
- Cleaned salary and date fields.
- Created a structured star schema using Power Pivot.
- Established relationships between fact and dimension tables.

## Data Analysis

The analysis focused on:

- Average salary by job role.
- Remote versus onsite salary comparison.
- Job demand by country.
- Top 10 most requested skills.
- Salary comparison based on degree requirements.
- Quarterly job posting trends throughout 2023.

## Dashboard

The Power BI dashboard includes:

- Interactive slicers for Role, Country, Date Range, and Job Type.
- Cross-filtering across visuals.
- Dynamic dashboard titles based on selections.
- Highlighting of top-performing values.
- Quarterly hiring trend analysis.
- Skill demand analysis.
- Remote versus onsite salary comparison.
- Job role demand versus salary comparison.

## Key Insights

- Specialized roles consistently offered higher average salaries.
- Remote positions remained competitive with onsite roles across several job categories.
- Job demand varied significantly across countries.
- Technical skills appeared frequently across multiple job categories.
- Hiring activity varied across quarters, indicating seasonal recruitment patterns.

## Project Structure

```text
Job-Market-Analytics-Dashboard/
│
├── Data/
│   └── Raw job posting dataset
│
├── Power Query/
│   └── Data cleaning and transformation
│
├── Power BI/
│   └── Job Market Analytics Dashboard.pbix
│
├── Images/
│   └── Dashboard screenshots
│
└── README.md
```

## Conclusion

This project demonstrates a complete business intelligence workflow, from cleaning raw job market data to building an interactive Power BI dashboard. By combining Power Query, Power Pivot, DAX, and visualization techniques, it transforms thousands of job postings into actionable insights on salaries, hiring trends, skill demand, and remote work, enabling more informed career decisions.
