
# Transportation Report

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiYmQwNTE0ZDItMGM4Mi00NjljLWFmYTUtNjljZjU3N2NkMzU2IiwidCI6IjM3NjFjYzBlLWMwNmMtNGY2Zi1iYjE2LWQwYTA1NDc0OGM4YiJ9

## Problem Statement

The "Transportation Report" dashboard provides valuable insights into the performance and utilization of city transit services. The primary goal of this dashboard is to improve the efficiency and effectiveness of public transportation routes and services.

#### Key Issues:

 - Route Optimization: Identifying underperforming routes and areas where adjustments are needed to better serve commuters.

 - Service Efficiency: Analyzing transit times, delays, and operational performance to enhance service reliability.

 - Ridership Analysis: Understanding patterns in commuter behavior, peak usage times, and demographic data to tailor services to meet demand effectively.

#### Goals:

 - Improve Route Planning: Offer data-driven recommendations for optimizing transit routes to reduce travel time and increase coverage.

 - Enhance Service Delivery: Identify and address inefficiencies in transit operations to improve overall service quality.

 - Support Decision-Making: Provide transit authorities and city planners with detailed insights to make informed decisions about future transit developments and enhancements.

By addressing these issues, the dashboard aims to contribute to a more efficient and user-friendly public transportation system, benefiting both transit authorities and city commuters.

### Steps Followed 

- Step 1: Four tables (buses, demographics, modified routes, and ridership) were uploaded as CSV files.
- Step 2: Opened Power Query Editor and reviewed data using "column distribution", "column quality", and "column profile" options.
- Step 3: Selected "column profiling based on entire dataset" to ensure comprehensive data analysis.
- Step 4: Identified and addressed issues with the "Arrival time" column, noting that null values were minimal (less than 1%).
- Step 5: Ignored blank values during average calculations as they are automatically excluded.
- Step 6: Report Design: Applied a theme to the report view for consistency.
- Step 7: Created visuals to represent various metrics and ratings, including peak times, bus utilization, and ridership trends.
- Step 8: Added interactive filters for detailed data exploration.
- Step 9: Data Analysis: Analyzed and cleaned the data according to the requirements before loading it into Power BI.

### Insights

#### Peak Hours and Utilization:
- Peak hour of operation is at 8:57 AM, indicating high demand during morning commute times.
- Lowest ridership hour is at 7:50 PM, suggesting lower demand during late evening.
- Bus utilization analysis shows 36 buses are properly utilized, 27 are over-utilized, and 19 are under-utilized.

#### Ridership Trends:
- Monthly ridership consistently increased from January to December.
- Notable decline in ridership from 2023 (85.8%) to 2024 (14.165%).

#### Route and Demographic Insights:
- The East-west express route is the busiest, while the South line is the least busy.
- Demographic data such as age, gender, and occupation could provide deeper insights into rider profiles and preferences.

#### Day and Time Analysis:
- Higher ridership observed on Sundays and Mondays compared to Fridays and Saturdays.
- Peak rider counts occur between 9 AM - 11:59 AM.

### Recommendations

#### Optimize Bus Routes:
- Consider increasing bus frequency during peak hours (8:57 AM) to accommodate higher demand.
- Evaluate and adjust routes that are under-utilized to improve coverage and efficiency, particularly focusing on the South line.

#### Enhance Service Delivery:
- Address the low utilization of buses by analyzing routes with low demand and possibly reassigning resources to more critical routes.
- Improve scheduling during low ridership hours (7:50 PM) to better align with actual demand.

#### Focus on Ridership Trends:
- Investigate the cause of the significant decline in ridership from 2023 to 2024 and implement strategies to address any identified issues.
- Utilize demographic insights to tailor services and promotions to specific age groups, genders, and occupations to boost ridership.

#### Adjust for Peak Times:
- Enhance service provision during the peak ridership periods (9 AM - 11:59 AM) and consider implementing additional buses or adjustments to schedules during these times.
- Address the increased ridership on Sundays and Mondays by ensuring adequate service levels and considering potential adjustments to fare or service offerings on these days.

By implementing these recommendations, the city can better align its transit services with actual demand and improve overall service quality for its commuters.

