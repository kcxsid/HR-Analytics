# HR Analytics 

**Author**: Sid Krishnakumar  
**Last Updated**: April 2025  
**Tools Used**: Python, Power BI, DAX, Power Query, Excel  
**Data**: Synthetic HR Dataset (7000+ employees)  


## Overview
This interactive Power BI dashboard provides a comprehensive view of HR metrics across the employee lifecycle — from hiring to performance, engagement, and attrition. Designed as part of a portfolio and interview presentation, this project demonstrates real-world analytics, data modelling using star schema, DAX measures, Power Query transformations, and dashboard design best practices.

*PLEASE NOTE: Synthetic data has been generated using python.*   

https://github.com/user-attachments/assets/6725143c-a746-459c-a468-47f8ac18018f


## Data Model
The data was structured using a star schema with the following tables:


**FactHiring**  
**FactAttrition**  
**FactEmployeePerformance**    

**DimEmployee**  
**DimDepartment**  
**DimRole**  
**DimLocation**  
**DimTime**  


## Dashboard Pages
| **Page**                     | **Description**                                                                                          |
|--------------------------|------------------------------------------------------------------------------------------------------|
| 🏠 Landing Page           | A user-friendly entry point with navigation buttons, instructions, KPI snapshot, and glossary links. |
| 📊 HR Overview            | High-level summary of total employees, gender and department breakdown, tenure, engagement, and trends. |
| 🔁 Attrition Analysis     | Deep dive into who left, why, and when — with breakdowns by role, age group, exit reason, and type.  |
| 🌟 Performance & Engagement | Tracks high performers, average engagement and training hours, and promotion insights.                |
| 🧩 Hiring Insights         | Displays hiring trends, source effectiveness, cost per hire, and new hire retention stats.           |
| 🧠 Attrition Drillthrough | Context-sensitive page showing filtered attrition KPIs, trends, and detailed leaver information.     |


### Landing Page
A clean and user-friendly entry point into the dashboard. Includes:  

Welcome message and instructions  
Navigation buttons to each page  
Key metric snapshot (e.g., total employees, attrition rate)  
Glossary and data dictionary access  
  
🎯 Purpose: Help users quickly understand the dashboard’s structure and navigate with ease.

![Image](https://github.com/user-attachments/assets/520ddd4e-2200-44ca-aaa8-65e64b13b855)

------------------------------------------------------------------------------------------------------------------------  
  
### HR Overview
A high-level summary of the current workforce, providing organizational health insights through:  
  
Total employee count  
Gender and department distribution  
Tenure bands (0–1 yr, 1–3 yrs, etc.)  
Average engagement and performance scores  
Headcount trends over time  
  
🎯 Purpose: Provide a comprehensive snapshot of the workforce across key demographics and metrics.  

![Image](https://github.com/user-attachments/assets/110dfc12-5e6c-4e70-a301-ea6a6baf96c4)
    
------------------------------------------------------------------------------------------------------------------------
### Attrition Analysis
Deep dive into employee exits, showing:  
  
Total attrition count and rate  
Voluntary vs involuntary exits  
Reasons for leaving (e.g., better offer, burnout)  
Attrition by department, role, gender, and age group  
Attrition over time  

🎯 Purpose: Identify attrition patterns, high-risk areas, and retention opportunities.  

![Image](https://github.com/user-attachments/assets/d77e259c-d57d-4f4e-b090-a4ab63cae784)

------------------------------------------------------------------------------------------------------------------------  
### Performance & Engagement
Tracks the health of talent across the organization using:  

High performer count and percentage  
Average engagement and training hours  
Promotions and promotion rate  
Heatmaps for engagement and performance distribution  
Drilldowns by role, department, or location  
  
🎯 Purpose: Help HR and managers understand how employees are performing, developing, and feeling.  
  
![Image](https://github.com/user-attachments/assets/f69f5493-0bfb-41ec-b40c-8a1d41940249)
 
------------------------------------------------------------------------------------------------------------------------ 
### Hiring Insights
Evaluates recruitment efficiency and outcomes via:  

Total hires and hiring trends over time  
Hiring cost and average cost per hire  
Hiring source effectiveness  
Retention of new hires  
Early attrition analysis  
  
🎯 Purpose: Optimize recruiting efforts by understanding what sources and strategies are most effective.  
  
![Image](https://github.com/user-attachments/assets/f883b0d2-d19c-4221-96b0-1846b651f5e0)

------------------------------------------------------------------------------------------------------------------------  
### Attrition Drillthrough
A dynamic, filter-driven page that shows detailed insights when users drill into specific roles, departments, or other segments. Includes:  
  
Attrition KPIs filtered to the selected group  
Exit reasons, tenure at exit, and engagement of leavers  
Average time to exit  
Tables of individual exited employees  
  
🎯 Purpose: Give stakeholders granular visibility into why specific teams or roles are experiencing turnover.  

![Image](https://github.com/user-attachments/assets/1c1bed88-8e8f-417e-a392-fbd0efbfa6a3)


## Key Metrics & Insights (Examples)
**✅ Total Hires, Attrition Rate, Avg Tenure**  
**🔁 % Exits Within 1 Year**  
**🧠 Avg Engagement & Performance of Leavers**  
**🔥 High Performer Attrition**  
**💸 Cost per Hire & Hiring Efficiency**  
**🕓 Avg Time to Exit**  
**📉 Voluntary vs Involuntary Exit Breakdown**  


## DAX & Power Query Highlights:
*Custom Engagement Band and Performance Band columns*  
*Measures for Net Change, Hiring Efficiency, Time to Exit, and more*  
*Power Query transformations: replacing "N/A" with nulls, data typing, and relationship setup*  
*Drillthrough filters for contextual deep-dives*  
*Conditional formatting in heatmaps and matrix visuals*  


## Key Takeaways
#### This dashboard demonstrates:
*Effective data storytelling for HR decision-makers*  
*Use of DAX to derive insights beyond raw data*  
*Proper data modelling using star schema*  
*Clear and consistent UI/UX design*  
*Strong documentation and maintainability*  


