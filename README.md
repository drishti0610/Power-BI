Goal: The project aims to build an interactive and dynamic dashboard of HR data to provide data-driven insights into employee attrition, workforce demographics, and job satisfaction to support HR decision-making.

Key Tasks:
1. Data Connection:
     Connected to a data source using Power Query.
     Performed data profiling to identify duplicates and empty rows for data accuracy.
   
2. Data Analysis and DAX:
     Created condition columns:
     - Attrition Count: If attrition is yes then 1 else 0. This column is used to calculate total attrition and attrition rate.
     - Sort Age: If the age band is under 25 then 1, else if 25 - 34 then 2, else if 35 - 44 then 3, else if 45 - 54 then 4, else 5. This column is used to sort age bands in a column chart.
       
     Created calculated columns and measures using DAX to compute essential metrics like:
     - Active Employees: Derived by subtracting attrition employees from total employees.
     - Attrition Rate: Derived by dividing attrition employees by total number of employees.
     - Average Age: Derived by using the AVERAGE function.
       
3. Interactive Dashboard:
     Designed a user-friendly interactive dashboard with the following key elements:
     - Cards: Displayed critical metrics such as total employees, attrition count, attrition rate, Active employees, and average age.
     - Bar Chart: Visualized education field performance and comparisons across different education degrees.
     - Column Chart: Displayed Employee counts across different age bands and genders.
     - Pie Chart: Displayed attrition count by departments.
     - Matrix: Displayed job satisfaction rating across job roles.
     - Donut Charts: Displayed attrition count for each age group and gender. Also added a card in each donut to show the attrition count for each age group by adding a filter for the age group. Note: Each age group has a different donut chart.
       
     Added dynamic Slicers for easy filtering by education degrees, enabling users to view data for a specific degree.

Outcome:
This dashboard helps HR teams and executives to:
- Identify high-risk areas for attrition.
- Analyze demographic trends affecting employee retention.
- Improve job satisfaction strategies to enhance retention.
- Make data-driven HR policies to optimize workforce stability.
