# Data Professional Survey Dashboard (Power BI)

An interactive Power BI dashboard that analyses a survey of 630 data professionals: where they live, what they earn, which programming languages they prefer, how happy they are at work, and how hard it was to break into the field.

![Dashboard Overview](screenshots/dashboard_overview.png)

## Objective
To explore the data professional job market and answer questions such as:
- Which job titles earn the highest average salary?
- Which programming languages do data professionals prefer?
- How satisfied are they with their salary and work/life balance?
- How difficult is it to break into data?

## Tools Used
- Power BI Desktop
- DAX (measures)
- Power Query (data cleaning and transformation)

## Dataset
- Source: [name of the survey / link to where you downloaded it]
- 630 survey responses
- Key fields: job title, country, age, gender, average salary, favourite programming language, happiness ratings (salary and work/life balance), difficulty of breaking into data

## Dashboard Features
- **KPI cards:** total survey takers (630) and average age (29.87)
- **Treemap:** survey takers by country
- **Bar chart:** average salary by job title
- **Stacked column chart:** favourite programming language by job title
- **Donut chart:** [difficulty to break into data / gender split]
- **Gauge charts:** happiness with salary (4.27 / 10) and work/life balance (5.74 / 10)

## Key Insights
1. **Data Scientists have the highest average salary**, well above Data Analysts and Database Developers.
2. **Python is the most popular language**, ahead of R and the others, across almost every job title.
3. **Respondents are happier with work/life balance (5.74/10) than with salary (4.27/10)**, so pay is the main source of dissatisfaction.

## Data Preparation
- Renamed columns and visual titles for readability
- [Changed data types, for example text to numbers for salary and ratings]


## What I Learned
- Building a multi-visual dashboard layout and choosing the right chart for each question
- Formatting KPI cards, gauges and donut charts
- Writing basic DAX measures

## How to Open
1. Download `data_professional_survey.pbix` from this repository.
2. Open it in Power BI Desktop (free to download from Microsoft).

## Author
**Mohamed Hasith M**
Sharjah, UAE
