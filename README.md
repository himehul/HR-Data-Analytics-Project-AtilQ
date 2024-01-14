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
\
2. **Data Transformation with Power Query:**
   Applied transformations, including header promotion, unpivoting, and other data cleaning processes.
\
\
![Temp 2](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/c56f1626-27e6-4e80-962c-05829e0a1c33)
\
\
3. **Parameter Creation:**
Implemented parameters for dynamic data filtering based on different months.
\
\
![Parameter 3](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/fe9873dc-78b2-4b38-b261-45edb4cf939d)
\
\
4. **Dynamic Data Transformation:**
 Developed a function, "GetData," to dynamically transform data and accommodate new entries seamlessly.
\
\
\
![Create Function 5](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/a2aad3cd-eea3-4ec3-8461-b4cd6afd9c5a)
![Adding Column Create Function 6](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/0bc423d7-0906-4895-b955-69088b00c448)
\
\
5. **Column Deletion:**
  Removed unnecessary columns to streamline the dataset.
\
\
![7 Deleted unessary columns](https://github.com/himehul/HR-Data-Analytics-Project--AtilQ/assets/139626006/818c07ce-fe7a-4641-8f89-4f95f98252ea)
\
\
8. **Loading Data to Power BI:**
 Successfully loaded the transformed data into Power BI for further analysis.
\
\
## Metrics Creation Using DAX

7. **Working Days Measures:**
   - Created measures to calculate the total number of working days, WFH count, present days, and presence percentage.

8. **Month Slicer Filter:**
   - Added a month column to create a slicer filter for the dashboard.

## Dashboarding

9. **WFH and Sick Leave Analysis:**
   - Developed measures to analyze the number of days employees choose to work from home and the sick leave percentage.

10. **Area Graph Analysis:**
    - Identified anomalies in the data using an area graph, leading to further investigation.

11. **Advanced Filtering:**
    - Applied advanced filtering to exclude data beyond the available range, resolving discrepancies in the analysis.

12. **Day of the Week Analysis:**
    - Created additional columns to determine the most and least preferred days for WFH, presenting findings in two tables.

13. **Final Dashboard:**
    - The completed dashboard provides a comprehensive overview, showcasing metrics related to employee attendance, WFH preferences, and sick leave patterns.

## Conclusion

This Power BI Dashboard serves as a valuable tool for HR decision-making by offering insights into employee work patterns and facilitating efficient data-driven management. Ongoing updates and improvements will be incorporated to ensure the dashboard remains a reliable resource for HR-related analytics at AtiQs Technologies.
