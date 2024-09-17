# Power BI Project
## Power BI projects showcase my skills as a data analyst, particularly in data visualization, transformation, and analysis. Through these projects, I demonstrate my ability to work with large datasets, create insightful dashboards, and provide actionable insights using Power BI’s advanced features such as DAX calculations, Power Query transformations.
### Key Skills

- **Data Modeling & Transformation:** I effectively clean, transform, and model raw data using **Power Query**, ensuring the data is structured for accurate analysis and visualization.

- **Advanced DAX Calculations:** My projects include dynamic measures and calculated columns using **DAX**, such as **CALCULATE**, **SELECTEDVALUE**, and **ALLSELECTED**, to perform complex calculations and filtering.
- **Interactive Dashboards:** I design interactive reports with slicers, drill-through pages, and dynamic visualizations, enabling users to explore data across various dimensions and categories.
- **Custom Visuals & Formatting:** I utilize custom visuals and design techniques, such as combo charts (line and bar), transparent fills, and data labels, to create aesthetically appealing and easy-to-interpret reports.
- **Performance Optimization:** I optimize report performance by utilizing relationships, minimizing data load time, and ensuring efficient DAX queries for faster user interaction.

### 1. Overlapping histogram with normal distribution curve-Penguins body mass by Sex

**Introduction**

Overlapping histograms with normal curve overlays are used to compare the distribution of a numerical variable across different groups such as male and female body mass. With this,we can glance the central tendency, spread, and skewness of the data within each group and also how well the data follows a normal distribution. The further apart the modes of distribution, the more significant the differences between groups.

**Processes**

- Data cleaning and processing using **Power Query**,including handling data missing,data duplicate,data type issues,data inconsistent
- Create **DAX** measures for the mean, standard deviation, and count for the data
- Create **DAX** measures to generate dynamic Bins of body mass
- Add combo bar and line chart to the canvas
- Create a **DAX** measure for finding the normal distribution curve for each sex
- Scale the distribution curve to the histogram by multiplying the result by the bin count and number of data points

**Dashboard Report**

The dashboard can be found in Power BI Public [here](https://app.powerbi.com/groups/me/reports/9bc3803a-c316-4435-a8c7-c65199040b46/ReportSectiond37320fe010d5870b59a?experience=power-bi). This dashboard enables users to filter by the count of bins, and focuses on the distribution of body mass across sex groups(Male and Female).

<img width="1096" alt="Screenshot 2024-09-16 at 15 31 53" src="https://github.com/user-attachments/assets/baa5fabb-c0c2-4889-99fa-333dd85600dd">

### 2. Performance Report: Plant Co. Sales Performance 

**Introduction**

This project explores the sales performance of a plant company by analyzing key performance metrics, including Sales revenue,Gross Profit, Quantity. Through dynamic dashboards and interactive reports, the goal is to provide insights into the overall sales performance by comparing YTD and PYTD, identify bottom 10 countries and products.

**Processes**

- Data cleaning and processing using Power Query to ensure accurate and usable data for analysis.
- Creation of DAX measures to calculate performance indicators and create dynamic filtering and titles.
- Visualize sales performance using Treemap,Waterfall Chart, Combo bar and line chart, Scatter chart.
- Implement Slicers for dynamic filtering based on Year,Gross Profit, Quantity, or Sales.
- Format visuals to ensure clarity and perofessional.

**Dashboard Report**

The dashboard can be found in Power BI Public [here](https://app.powerbi.com/groups/0f9c129b-8a90-44e6-af6a-a1d4a98d914e/reports/488249db-f967-47ba-90d9-3ce19fbca54f/0fecfaafeb70bc3dc0a0?experience=power-bi). This report allows users to filter by Year,Gross Profit, Quantity, or Sales.

<img width="1141" alt="Screenshot 2024-09-17 at 07 32 37" src="https://github.com/user-attachments/assets/34209c74-e14f-47b3-9e5c-c5ce39a15fc8">


