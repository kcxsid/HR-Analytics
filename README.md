# HR-Analytics

Author: Sid Krishnakumar
Last Updated: April 2025
Tools Used: Power BI, DAX, Power Query, Excel
Data: Synthetic HR Dataset (7000+ employees)


## Overview
This interactive Power BI dashboard provides a comprehensive view of HR metrics across the employee lifecycle — from hiring to performance, engagement, and attrition. Designed as part of a portfolio and interview presentation, this project demonstrates real-world analytics, data modelling using star schema, DAX measures, Power Query transformations, and dashboard design best practices.


https://github.com/user-attachments/assets/6725143c-a746-459c-a468-47f8ac18018f


## Data Model
The data was structured using a star schema with the following tables:

#### Fact Tables:
FactHiring
FactAttrition
FactEmployeePerformance

#### Dimension Tables:
DimEmployee
DimDepartment
DimRole
DimLocation
DimTime


## Dashboard Pages
Page	                                Description
Landing Page	                 Welcome message, navigation buttons, instructions, and KPI snapshot
HR Overview	                   Headcount trends, tenure distribution, engagement and attrition summaries
Attrition Analysis	           Drilldowns by department, age group, role, voluntary vs involuntary exits
Performance & Engagement	     Tracks high performers, training, engagement bands, promotion insights
Hiring Insights	               Hiring trends, cost per hire, source effectiveness, and retention of new hires
Drillthrough Page	             Dynamic view for exploring attrition details by department, role, etc.


## Key Metrics & Insights (Examples)
✅ Total Hires, Attrition Rate, Avg Tenure
🔁 % Exits Within 1 Year
🧠 Avg Engagement & Performance of Leavers
🔥 High Performer Attrition
💸 Cost per Hire & Hiring Efficiency
🕓 Avg Time to Exit
📉 Voluntary vs Involuntary Exit Breakdown


## DAX & Power Query Highlights:
Custom Engagement Band and Performance Band columns
Measures for Net Change, Hiring Efficiency, Time to Exit, and more
Power Query transformations: replacing "N/A" with nulls, data typing, and relationship setup
Drillthrough filters for contextual deep-dives
Conditional formatting in heatmaps and matrix visuals


## Key Takeaways
#### This dashboard demonstrates:
Effective data storytelling for HR decision-makers
Use of DAX to derive insights beyond raw data
Proper data modelling using star schema
Clear and consistent UI/UX design
Strong documentation and maintainability
