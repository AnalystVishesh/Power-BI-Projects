
# Customer Retention Dashboard

#### Note : This project is a part of virtual internship under Pwc Switzerland organized by Forage.

### Dashboard Link :  https://app.powerbi.com/view?r=eyJrIjoiMDZhOWY5ZGMtZTE5ZC00YjhmLWI3NzYtNjEyMTU2MjYxM2Q0IiwidCI6IjM3NjFjYzBlLWMwNmMtNGY2Zi1iYjE2LWQwYTA1NDc0OGM4YiJ9

## Problem Statement
PhoneNow's Retention Manager has tasked us with developing a customer retention dashboard. The objective is to identify customers at risk of terminating their contracts before they decide to leave. This proactive approach will enable the retention team to implement targeted interventions to prevent churn and enhance customer loyalty.

#### Key Issues

 - High Customer Acquisition Costs:
        Acquiring customers in the telecom industry is costly, making it crucial to retain existing customers to maximize return on investment.

 - Reactionary Retention Strategies:
        Current retention efforts are reactionary, engaging customers only after they have already terminated their contracts.

 - Lack of Predictive Insights:
        There is a need to predict which customers are at risk of leaving, allowing for timely and effective retention strategies.

 - Ineffective Data Analysis Tools:
        Previous customer analyses using Excel have been ineffective, leading to a need for more sophisticated data visualization and analysis tools.

 - Need for Clear Visualization:
        Management requires clear, self-explanatory visualizations to understand customer behavior and make informed decisions.

#### Goals

 - Predict Customer Churn:
        Develop predictive models to identify customers at risk of leaving, allowing the retention team to take preemptive action.

 - Visualize Customer Data:
        Create a comprehensive dashboard that clearly visualizes key metrics and customer data, making it easy for management to understand and act upon.

 - Enhance Retention Strategies:
        Provide actionable insights that can inform targeted retention strategies to reduce churn rates.

 - Improve Customer Understanding:
        Gain a deeper understanding of customer demographics, behaviors, and service usage to tailor retention efforts effectively.

 - Streamline Data Analysis:
        Utilize advanced data visualization and analysis tools to overcome the limitations of previous Excel-based analyses.

## Steps Followed

- Step 1: Data Collection:
        Collected data on customers who left within the last month, the services they signed up for, customer account information, and demographic info.
        Data included: tenure, contract type, payment method, monthly charges, total charges, number of tickets opened, gender, age range, partner status, and dependents.

- Step 2: Data Upload and Initial Transformation:
        Uploaded the provided CSV files into Power Query for initial cleaning and transformation.

- Step 3: Building Conditional Columns:
        Created a conditional column "Risk category" to categorize customers based on tenure:
        Created a conditional column "Loyalty" to categorize customers based on tenure:
- Step 4: Data Cleaning: Handled missing values, removed duplicates, and corrected inconsistencies to ensure data quality.

- Step 5: Data Modeling: Defined relationships between tables and created necessary calculations to build a robust data model in Power BI.

- Step 6: Data Visualization: Developed interactive dashboards to visualize key metrics such as customer churn rate, risk categories, and loyalty segments.
    Used various visualizations including line charts, bar charts, and tables to present insights clearly.

- Step 7: Analysis: Conducted a detailed analysis to identify patterns and trends in customer behavior.
    Analyzed factors such as tenure, service usage, and demographic info to determine their impact on retention.
    
### Insights    
- Significant Risk of Customer Churn: The dataset reveals a substantial number of at-risk customers (1,869), indicating a critical need for targeted retention strategies. The financial impact of these potential losses is considerable, with yearly charges amounting to $2.86 million.

- High Volume of Support Tickets: The volume of technical and administrative support tickets is notably high, suggesting systemic issues that could be contributing to customer dissatisfaction. Addressing these support challenges could be pivotal in reducing churn rates.

- Contract Type Correlation: Customers with month-to-month contracts exhibit the highest churn rates compared to those with longer-term commitments. This indicates an opportunity to implement strategies that incentivize longer-term contracts, potentially improving overall retention.

- Impact of Subscription Duration: Customers with shorter subscription durations (less than a year) are at higher risk of churning. This underscores the importance of engaging and retaining new customers early in their lifecycle to prevent early attrition.

- Effectiveness of Payment Methods: There is a notable correlation between payment methods and churn rates. Customers using electronic checks have a higher churn rate compared to those using automatic payments. Streamlining payment processes and promoting more convenient options could help in mitigating churn.

- Service Type Influence: The analysis highlights that customers using fiber optic services experience a higher churn rate compared to those on DSL or with no service. This could signal potential service quality issues or dissatisfaction that need addressing.

- Demographic Insights: A significant proportion of at-risk customers are senior citizens and those with partners or dependents. Tailoring retention efforts to address the unique needs of these groups may enhance the effectiveness of retention strategies.

- Paperless Billing Adoption: The high adoption rate of paperless billing among at-risk customers suggests a shift towards digital preferences. Ensuring that digital billing and communication channels are optimized and user-friendly could improve customer satisfaction and retention.

- Churn Analysis by Internet Service: The distribution of churn by internet service type shows that customers with fiber optic subscriptions are more likely to churn. Investigating the specific issues faced by fiber optic users and improving service quality could help reduce churn in this segment.
    
### Recommendations

 - Implement Targeted Retention Programs:
        Develop targeted retention programs focusing on high-risk customers, particularly those with short subscription durations and those on month-to-month contracts. This could include personalized offers, loyalty rewards, and tailored communication.

 - Revise Contract Incentives:
        Introduce incentives for customers to switch to longer-term contracts, such as discounted rates for one-year or two-year commitments. This could help lock in customers and reduce churn.

 - Enhance Support Services:
        Invest in improving support services, including faster response times and better resolution of technical and administrative issues. Consider implementing advanced support technologies or additional training for support staff.

 - Optimize Payment Options:
        Evaluate and streamline payment methods to make them more convenient for customers. Promote automatic payment options and explore potential enhancements to the electronic check system.

 - Improve Service Quality:
        Conduct a detailed analysis of the fiber optic service to identify and address quality issues. Implement quality improvement measures and communicate these enhancements to customers.

 - Develop Demographic-Specific Strategies:
        Create retention strategies tailored to specific demographic groups, such as senior citizens and customers with partners or dependents. This could involve specialized customer service approaches or targeted promotions.

 - Strengthen Digital Communication:
        Enhance digital communication and billing systems to ensure a seamless and user-friendly experience. This could involve improving the functionality of digital billing platforms and increasing engagement through digital channels.

 - Monitor and Adjust Strategies:
        Continuously monitor the effectiveness of implemented strategies and adjust them based on performance data and customer feedback. Regularly review churn metrics and support ticket trends to ensure ongoing improvements.

By addressing these implications and following the recommendations, the organization can better manage customer retention, reduce churn, and improve overall customer satisfaction.
