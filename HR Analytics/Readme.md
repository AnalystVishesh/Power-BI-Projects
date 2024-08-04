# HR Analytics Dashboard
### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiZjNhODU3NDYtZTgxNC00MWY1LTliY2EtZDNiNjJlM2FjYjk1IiwidCI6IjM3NjFjYzBlLWMwNmMtNGY2Zi1iYjE2LWQwYTA1NDc0OGM4YiJ9

## Problem Statement

The "HR Analytics Dashboard" equips HR professionals with critical insights into headcount trends, retention rates, and turnover statistics. The primary goal is to facilitate informed decision-making to enhance workforce management and organizational growth.

#### Key Issues

 - Headcount Trends: Monitoring workforce size and composition fluctuations.
 - Retention Rates: Identifying patterns in employee retention to improve retention strategies.
 - Turnover Statistics: Analyzing turnover rates to develop targeted retention strategies and reduce attrition.

#### Goals

 - Optimize Workforce Planning: Provide data-driven insights for effective workforce management.
 - Boost Employee Retention: Identify and address factors affecting employee retention.
 - Support Strategic HR Decisions: Deliver detailed visualizations to aid in strategic talent management decisions.

By addressing these issues, the dashboard empowers organizations to optimize their workforce, foster a culture of engagement, and enhance overall HR management practices.

## Steps Followed

#### Data Preparation:
- Step 1 : CSV files were uploaded into Power Query: People Data Table: Included columns such as EmployeeID, gender, race, birthdate, education, location, location_city, marital status, and employment status.
            People Employment History Table: Included columns such as employee_id, first_name, last_name, department, sub-department, first_level_manager, second_level_manager, third_level_manager, fourth_level_manager, job_level, salary, hire_date, term_date, term_type, term_reason, and active_status.

- Step 2 : Data Transformation:
        Birthdate to Age Calculation: The birthdate column in the People Data Table was used to calculate the age of each employee.
        Active Status Transformation: In the People Employment History Table, the active status column was transformed from binary values (1/0) to categorical values (yes/no).

- Step 3 : Fact and Dimension Tables Creation:
        People Fact Table:
            The People Employment History Table was referenced to create the People Fact Table.
            Redundant columns such as department and sub-department were removed, retaining only the department key to establish relationships.
        Dimension Tables:
            Department Dimension Table: Created to hold unique department-related data.
            Term Dimension Table: Created to categorize termination reasons and types.
            Job Level Dimension Table: Created to define job levels across the organization.
            Manager Dimension Table: Created to map hierarchical managerial relationships.
            Education Dimension Table: Created to categorize employee education levels.
            Location Dimension Table: Created to define geographic locations.
            Marital Status Dimension Table: Created to categorize marital status data.
        Date Table: A separate Date Table was created to facilitate time-based analysis.

- Step 4 : Data Integration and Relationship Building:
        Each dimension table was merged with the People Fact Table to establish relationships.
        Final columns in the People Fact Table included: employee id, first name, last name, full name, salary, hire date, term date, active status (yes/no), employment status (full-time/contract), department key, job level key, term key, demographic key, education key, marital status key.

- Step 5 : Model Evaluation:
        Data was loaded into Power BI and the data model was evaluated to check relationships between tables for accuracy and cardinality.
        Ensured all relationships were correctly established and validated for data integrity.

- Step 6 : Visualization and Reporting:
        Created interactive visualizations for each key metric, organized into separate pages:
            Cover Page: Provides navigation options to Headcount, Retention, and Turnover pages.
            Headcount Page: Displays metrics related to employee headcount.
            Retention Page: Shows retention rates and related insights.
            Turnover Page: Visualizes turnover statistics and trends.

By following these steps, a comprehensive HR Analytics dashboard was developed, providing valuable insights into workforce dynamics, aiding HR professionals in making data-driven decisions.

## Insights

#### Departmental Distribution:
 - Software has the highest headcount, indicating a strong emphasis on technical roles, which may reflect a focus on product development or IT.
 - Sales also has a substantial number of employees, highlighting the importance of revenue generation and customer acquisition.

#### Location Trends:
 - A significant majority of employees are remote (80%), suggesting a strong shift towards remote work. This shift implies potential cost savings on physical office space and a need for robust remote work infrastructure.

#### Job Level Distribution:
 - A large proportion of employees are individual contributors (75%), indicating a broad base of operational staff. The relatively smaller number of directors and CEOs suggests a flatter organizational structure or a focus on decentralized decision-making.

#### Gender Distribution:
 - The workforce is predominantly male (61%), which may highlight an area for potential improvement in gender diversity initiatives.

#### Marital Status:
 - A significant majority of employees are single (71%), which could influence benefits planning, work-life balance policies, and employee engagement strategies.

#### Retention Rates:
 - The overall retention rate is strong at 83.6%, indicating a stable workforce. However, departmental variations suggest that some areas may benefit from additional retention strategies.

#### Retention by Department:
 - Operations has the highest retention rate (89.2%), which may be due to job satisfaction or career development opportunities in this department. Conversely, Customer Service and Finance have lower retention rates, pointing to potential areas for improvement in employee engagement or support.

#### Retention by Job Level:
 - Team Leads exhibit the highest retention rate (91.8%), suggesting effective support at this level. Lower retention among Directors may indicate a need for enhanced support or career advancement opportunities.

#### Turnover Rate:
 - The overall turnover rate is relatively high at 37.4%, signaling potential issues in employee satisfaction or competitive pressures.

#### Turnover by Department:
 - R&D and Sales have the highest turnover rates, which might indicate challenges such as project pressure or competitive compensation.

#### Turnover Reasons:
 - The most common reasons for leaving include finding a better opportunity and seeking more flexible benefits, suggesting that competitive compensation and benefits packages are critical for retention.

#### Voluntary vs. Involuntary Turnover:
 - Voluntary turnover is significantly higher (82%), highlighting the need to address employee satisfaction and career growth opportunities.

## Recommendations

#### Optimize Workforce Planning:
 - Leverage the high remote headcount and departmental distributions to address potential challenges related to remote work and departmental resources.

#### Enhance Diversity and Inclusion:
 - Review diversity and inclusion practices to ensure a more balanced and inclusive work environment.

#### Focus on Retention Strategies:
 - Improve retention in departments with lower rates and enhance support for high turnover areas. Tailor retention strategies to address specific departmental or role-based challenges.

#### Competitive Positioning:
 - Ensure competitive benefits and career opportunities to reduce voluntary turnover. Attractive compensation packages and career development opportunities are key to maintaining a stable workforce.

#### Employee Engagement: 
 - Address common reasons for turnover, such as finding better opportunities and seeking more flexible benefits, to improve overall employee satisfaction and retention.

#### Leadership Support:
 - Enhance support for Directors and other leadership roles to improve retention at higher levels and ensure career growth opportunities.



