##📊 US States Population Analysis (1950 – 2015)

Interactive Power BI report exploring population trends for every U.S. state from 1950 through 2015.
The project highlights long-term growth patterns and regional differences, providing both high-level summaries and detailed state-by-state insights.

#📝 Project Overview

The goal of this dashboard is to analyze and visualize population change across the United States over 65 years.
Users can slice the data by Census Region, Division, or individual state to uncover patterns, compare areas, and evaluate growth across any custom time interval.



| Tool / Language      | Purpose                                                                |
| -------------------- | ---------------------------------------------------------------------- |
| **Excel**            | Initial data inspection & light cleaning                               |
| **Power Query**      | Data transformation and shaping                                        |
| **Power BI Desktop** | Data modeling, relationships, and interactive visualization            |
| **DAX**              | Calculated measures, dynamic growth metrics, conditional logic         |
| **File Formats**     | `.pbix` (Power BI development file) and `.png` (static preview images) |

📂 Data Source

Population estimates from U.S. Census Bureau (historical dataset covering 1950 – 2015 by state).

✨ Features & Highlights

Problem Statement
Understand how populations have evolved across U.S. states, and identify which regions and divisions have experienced the most growth since 1950.

Dashboard Goals

Provide a single, interactive view of population by Region, Division, and State.

Enable time-series analysis to track growth trends and compare different areas.

Key Visuals

Map with regional and country borders, interactive tooltip showing each state’s full 1950-2015 population trend.

Hierarchical Slicer (Region → Division → State) filtering all visuals simultaneously.

Table summarizing 2015 population by region, division, and country.

Bar Chart counting census divisions by census region.

Ribbon Chart showing population changes by year and state.

Growth Table & Slicer on a second page to calculate population growth between any two selected years.

Clone the repository, open the .pbix file in Power BI Desktop, and explore the visuals interactively or view the included .png previews.

Feel free to fork this project, adapt it to new datasets, or contribute additional visuals and insights!
