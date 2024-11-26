
# Sales-Insights

### Dashboard Link : https://app.powerbi.com/groups/me/reports/cdb4ae84-25ca-4814-9448-f516256915ce?ctid=3f2ad3ca-12c2-49b3-ab25-6aea2f8855b9&pbi_source=linkShare

## Problem Statement

AtliQ Hardware's Sales Director faces challenges in tracking and analyzing sales performance across dynamically growing markets in India. Regional managers provide verbal and Excel-based reports, often lacking accuracy and clarity. The abundance of Excel files complicates data interpretation, hindering his 
ability to make informed decisions. To address this, a centralized dashboard is needed to provide real-time, actionable insights into sales trends and performance. The goal is to replace cumbersome manual reporting with a data-driven solution that offers clear visualizations, enabling him to quickly identify areas for improvement and make strategic decisions to boost sales.



### Steps followed 

- Step 1 : Data Acquisition:

  Source File: Obtained the SQL file containing the sales data required for analysis.

- Step 2 : Database Connectivity:

  Power BI Connection: Connected Power BI to the  SQL database using the appropriate database connectivity settings.
  
  Configuration: Set up the connection parameters in Power BI to access and import data from the SQL file
- Step 3 : ETL Process:

  Extract:Loaded data from the SQL database into Power BI using the SQL connector.

  Transform: Cleaned and processed the data using Power BI’s Query Editor.

  Load:Imported the cleaned and transformed data into Power BI’s data model for analysis and visualization.
- Step 4 : Dashboard Design:

  Created visualizations and interactive elements in Power BI.

  Arranged the dashboard for clarity and usability.
 
- Step 5 : Visual filters (Slicers) were added for two fields named "Year" & "Months", 
- Step 6 : Two card visuals were added to the canvas, one representing Revenue & other representing Sales Quantity.

           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 7 : Stacked bar charts were also added to the report design area representing Revenue by Markets, Sales QTY by Markets, Top 5 Customers & Top 5 Products 
- Step 8 : Line Chart was used to represent revenue trend over the years,


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Revenue = 984.81M

 
           
### [2] Total QTY of Sales = 2.43M
  
   
 ### [3] Some other insights
 
 ### Revenue Trend
 
 1.1) The revenue trend starts strong in early 2018, peaking at the start of 2018 at over 40M. 
 
 1.2) There is a noticeable decline afterward, with fluctuations but a general downward trend, especially steeply falling towards early 2020.
 
 1.3)The revenue trend a significant reduction in revenue.
 
