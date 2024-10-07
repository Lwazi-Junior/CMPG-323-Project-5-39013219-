# NWU Tech Trends Benefit Realisation Power BI Report

## Project Overview
This project focuses on the creation of a Power BI report to visualize the benefits realized by NWU Tech Trends from its various projects and clients. The report includes interactive visuals and analysis features that allow stakeholders to monitor key metrics such as time saved, project distribution, and client performance. It incorporates advanced AI features for deeper insights and enables easy filtering and drill-through capabilities.

## Report Pages

### 1. High-Level Metrics
The **High-Level Metrics** page provides an overview of the most important data points relevant to NWU Tech Trends’ projects and clients.

- **Total Projects**: Shows the total number of active projects across all clients.
- **Total Clients**: Displays the total number of clients served by NWU Tech Trends.
- **Total Savings per Client**: Bar chart visualizing the total savings accumulated by each client.
- **Project Distribution by Client**: Donut chart showing the distribution of projects among different clients.


### 2. Project Monitoring
The **Project Monitoring** page provides detailed insights into each project, including time saved and savings.

- **Project Table**: Lists all projects along with the client name, start date, end date, and time saved.
- **Time Saved per Project**: Bar chart showing the total time saved for each project.
- **Date Filter**: A slicer to filter projects based on their start or end date.
- **Decomposition Tree**: An AI feature that breaks down the total savings by project, client, and other factors.

### 3. Client Monitoring
The **Client Monitoring** page focuses on monitoring client performance and savings.

- **Total Savings per Client**: Bar chart displaying the total savings for each client.
- **Proportion of Savings by Client**: Pie chart showing the proportion of savings for each client.
- **Savings per Client Over Time**: Line chart showing the progression of savings over time for each client.
- **Client Filter**: A slicer that allows users to filter by specific clients.
- **Key Influencers**: An AI-driven visual identifying factors that influence client savings the most.

## Usage Instructions

### Navigating the Report
- Use the **tabs** at the bottom of the report to switch between **High-Level Metrics**, **Project Monitoring**, and **Client Monitoring** pages.
- **Slicers** (filters) are available on each page to refine the data by client, date range, and project type.
- Hover over visuals to see additional details and **tooltips** providing further context.

### Drill-Through Functionality
- You can right-click on any visual (such as a specific project or client) to **Drill Through** into more detailed insights about that data point. 
- This feature allows for deeper analysis of projects and clients by navigating to dedicated pages.

### Filters and Interactions
- Use the slicers provided on the right-hand side to filter the data by:
  - **Client Name**
  - **Project Type**
  - **Date Range**
- Interacting with one visual will automatically update the others to reflect the filtered data, ensuring cohesive analysis across the entire report.

### Data Source
- The data used for this report is sourced from an Excel file provided by NWU Tech Trends, containing information on projects, clients, time saved, and savings.

## Calculations and Measures

- **Project Duration**: A calculated column that computes the duration of each project in days using the `DATEDIFF` function.
- **Total Savings**: A key measure that calculates the total savings across all projects using the `SUM` function on the `Savings` column.

## AI Features
This report leverages Power BI’s built-in AI features for deeper insights:

1. **Key Influencers** (Client Monitoring page): Identifies factors that influence client savings.
2. **Decomposition Tree** (Project Monitoring page): Breaks down savings hierarchically by project, client, and project type.

## How to Refresh Data
- This report is connected to an Excel data source. If the data source is updated, simply refresh the report to reflect the latest data.
- In Power BI Desktop, go to **Home > Refresh** to refresh the data.
- In Power BI Service, the report will automatically update if it is connected to a live data source.

## Publishing and Sharing the Report
- The report has been published to Power BI Service. It can be accessed through the following link: [Power BI Report Link](#).
- Stakeholders can interact with the report online, filtering and drilling through as needed.
- For sharing, ensure that the report is shared with stakeholders who have access to Power BI Service.

## Reference List
The following resources were used in the development of this Power BI report:

1. Chacon, S. & Straub, B., 2014. *Pro Git*. 2nd ed. Apress.
2. Esposito, D., 2021. *Modern Web Development with ASP.NET Core 5*. 1st ed. Packt Publishing.
3. Freeman, A., 2018. *Pro ASP.NET Core MVC 2*. 7th ed. Apress.
4. Galloway, J., 2020. *Professional ASP.NET Core 3.0: Building Modern Web Apps with .NET*. 1st ed. Wrox Press.
5. Garrett, J.J., 2011. *The Elements of User Experience: User-Centered Design for the Web and Beyond*. 2nd ed. New Riders.
6. Harrington, J., 2009. *Relational Database Design and Implementation*. 3rd ed. Morgan Kaufmann.
7. Jorgensen, M., 2019. *SQL Server 2019 Administration Inside Out*. 1st ed. Microsoft Press.
8. Loeliger, J. & McCullough, M., 2012. *Version Control with Git*. 2nd ed. O'Reilly Media.
9. Meszaros, G., 2007. *xUnit Test Patterns: Refactoring Test Code*. 1st ed. Addison-Wesley Professional.
10. Price, M., 2018. *C# 7 and .NET Core 2.0 High Performance: Build Highly Performant Applications*. 1st ed. Packt Publishing.
11. Rubin, K.S., 2012. *Essential Scrum: A Practical Guide to the Most Popular Agile Process*. Addison-Wesley.
12. Schwaber, K. & Sutherland, J., 2017. *The Scrum Guide*. Available at: https://scrumguides.org.
13. Silberschatz, A., Korth, H.F. & Sudarshan, S., 2020. *Database System Concepts*. 7th ed. McGraw-Hill Education.
14. Teorey, T.J., Lightstone, S. & Nadeau, T., 2010. *Database Modeling and Design: Logical Design*. 5th ed. Morgan Kaufmann.
15. UiPath, 2020. *UiPath Studio Documentation*. Available at: https://docs.uipath.com/studio/docs.
16. Unger, R. & Chandler, C., 2012. *A Project Guide to UX Design*. 2nd ed. New Riders.
17. Yochay, I., 2020. *Testing ASP.NET Core Applications*. Available at: https://docs.microsoft.com/en-us/aspnet/core/test/.

## Contact Information
For any questions or feedback regarding this Power BI report, please contact [Lwazi Nhlapo] at [lwazijayr@gmail.com].
