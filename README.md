# HR-Data-Analytics-Project-AtilQ

## Project Overview

This project focuses on building a Power BI Dashboard for analyzing employee data at AtiQs Technologies, a software and data solution company. The primary goal is to assist the HR manager in efficiently handling HR-related queries, such as understanding working preferences, sick leave percentages, and overall employee attendance patterns.

## Aim's Grid

1. **Purpose:**
   The purpose of this project is to streamline HR processes at AtiQs Technologies by developing a comprehensive Power BI Dashboard for employee data analysis.

2. **Stakeholders:**
   Primary stakeholders include the HR manager and other key decision-makers responsible for human resources and employee management.

3. **End Result:**
   The end result is an insightful Power BI Dashboard providing a holistic view of employee work patterns, preferences, sick leave trends, and overall attendance metrics.

4. **Success Criteria:**
   The success of the project is measured by:
      - Efficient handling of HR-related queries by the HR manager.
      - Clear visualization of working preferences, such as frequent work-from-home patterns on specific days.
      - Accurate calculation and representation of sick leave percentages.
      - Implementation of dynamic data transformations to accommodate future entries seamlessly.
      - A user-friendly dashboard providing actionable insights for HR decision-making.

## Data Gathering and Transformation

1. **Data Loading and Duplication:**
   Loaded the employee data and created a duplicate for use as a format template for future entries.
\
\
![Template 1](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/ba80cab3-c76c-4194-8664-282191f4850f)
#
2. **Data Transformation with Power Query:**
   Applied transformations, including header promotion, unpivoting, and other data cleaning processes.
\
\
![Temp 2](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/c56f1626-27e6-4e80-962c-05829e0a1c33)
#
3. **Parameter Creation:**
Implemented parameters for dynamic data filtering based on different months.
\
\
![Parameter 3](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/fe9873dc-78b2-4b38-b261-45edb4cf939d)
#
4. **Dynamic Data Transformation:**
 Developed a function, "GetData," to dynamically transform data and accommodate new entries seamlessly.
\
\
![Create Function 5](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/a2aad3cd-eea3-4ec3-8461-b4cd6afd9c5a)
![Adding Column Create Function 6](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/0bc423d7-0906-4895-b955-69088b00c448)
#
5. **Column Deletion:**
  Removed unnecessary columns to streamline the dataset.
\
\
![7 Deleted unessary columns](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/818c07ce-fe7a-4641-8f89-4f95f98252ea)
#
6. **Loading Data to Power BI:**
 Successfully loaded the transformed data into Power BI for further analysis.
#
##
## Metrics Creation Using DAX

7. **Working Days Measures:**
Created measures to calculate the total number of working days, WFH count, present days, and presence percentage.
\
![8 Total Working Days measure](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/2e301065-344e-44aa-a822-a54a2480c1a7)
#
![9 WFH Count'](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/e96e60c2-742b-46d9-b444-22bf97d3baf6)
#
![10 present days](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/140269d2-49ee-42ca-99e7-40e29d01f840)
#
![11 Presence %](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/35c0a1b7-8c89-4fed-9b51-831d6c552896)
#
8. **Month Slicer Filter:**
Added a month column to create a slicer filter for the dashboard.
\
![12 Month Column](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/38dc02aa-0096-4332-8886-04164938bd89)
![12 Slicer](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/9288da89-5192-4641-8456-6549a9daf168)
#
##
## Dashboarding

9. **WFH and Sick Leave Analysis:**
 Developed measures to analyze the number of days employees choose to work from home and the sick leave percentage.
\
![13 WFH%](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/03dea268-7b27-4a60-a280-1f75cf5876b7)
![14 SL%](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/3fc5bf3c-fae9-4bf3-ae01-2de1fd70f2fb)
#
10. **Area Graph Analysis:**
Identified anomalies in the data using an area graph, leading to further investigation.
\
![16](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/d8cd7e5e-7723-4022-a47e-bb14165d58b0)


#
11. **Advanced Filtering:**
Discovered a dip near June 27, 2022, prompting investigation due to data limitations until June 17. For that applied advanced filtering to exclude data beyond the available range, resolving discrepancies in the analysis.
\
![16 Excel](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/23ea03aa-b840-4fc8-a388-6b867eb49a37)
![17](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/96393adb-45f4-42ab-98af-d7d4fea9f893)
#
12. **Day of the Week Analysis:**
Created additional columns to determine the most and least preferred days for WFH, presenting findings in two tables.
\
![18 New Colm Day of week](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/512d4caf-d601-452d-8d37-e4f3ed66d128)
![19](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/902e4eda-5668-474c-a6f2-59281151972f)

#
13. **Final Dashboard:**
The completed dashboard provides a comprehensive overview, showcasing metrics related to employee attendance, WFH preferences, and sick leave patterns.
\
![20](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/81a79ad2-1794-446f-a639-027f145a47ef)

#
## Conclusion

1. **Identifying Employee with 0% Presence:**
   - Through our analysis, it was revealed that Ayanna Atkins is an employee with 0% presence in the month of June 2022.
   \
![Ayana Atkins](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/55668d13-2a44-4740-8028-51d4dbb050d8)
#
2. **Trends in Presence Percentage:**
   - The area charts illustrate a declining trend in overall presence percentage, attributed to an increase in both Work From Home (WFH) percentage and Sick Leave percentage.
   - A plausible explanation for this trend could be the warmer temperatures, potentially leading to an increase in employee illnesses, prompting a preference for working from home.
\
![Conclusion 2](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/068a1f2e-5ba0-44d3-9e4d-e2a2b0aae4b0)
#
3. **Strategic Insights for Team Meetings:**
   - Analyzing the data by day of the week, it is evident that Thursday and Friday are the days with the highest incidence of employees opting to work from home.
   - With detailed analysis, it can be inferred that only 85% of the workforce is doing Work from Office on Fridays.
   - Consequently, for maximum attendance in team meetings, AtiQs Technologies may consider scheduling them on Mondays, when the employee presence percentage is at its peak.
\
![Concluion3](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/2b7b5258-1d4e-4cb5-a84e-00171a165bdf)
#
In conclusion, the insights derived from this analysis provide valuable information for strategic decision-making, allowing AtiQs Technologies to optimize team collaboration and address factors influencing employee attendance and work preferences. The detailed examination of individual cases, trends, and strategic considerations contributes to a holistic understanding of the dynamics within the organization.
