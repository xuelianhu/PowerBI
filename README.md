# Power BI Project
## Welcome Power BI world. Here're my self-improvement visulisation projects.
### Overlapping histogram with normal distribution curve-Penguins body mass by Sex
**Introduction**

Overlapping histograms with normal curve overlays are used to compare the distribution of a numerical variable across different groups such as male and female body mass. With this,we can glance the central tendency, spread, and skewness of the data within each group and also how well the data follows a normal distribution. The further apart the modes of distribution, the more significant the differences between groups.

**Processes**

- Data cleaning and processing using **Power Query**
- Create **DAX** measures for the mean, standard deviation, and count for the data
- Create Dynamic Bins of body mass
- Add combo bar and line chart to the canvas
- Format Bars
- Create a **DAX** measure for finding the normal distribution curve for each sex
- Scale the distribution curve to the histogram by multiplying the result by the bin count and number of data points
- Format lines to a smooth curve

**Dashboard Report**

The dashboard can be found in Power BI Public [here](https://app.powerbi.com/groups/me/reports/9bc3803a-c316-4435-a8c7-c65199040b46/ReportSectiond37320fe010d5870b59a?experience=power-bi). This dashboard enables users to filter by the count of bins, and focuses on the distribution of body mass across sex groups(Male and Female).

<img width="1096" alt="Screenshot 2024-09-16 at 15 31 53" src="https://github.com/user-attachments/assets/baa5fabb-c0c2-4889-99fa-333dd85600dd">
