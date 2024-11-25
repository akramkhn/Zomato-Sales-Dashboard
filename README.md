Project Overview

The Zomato Sales Dashboard is a comprehensive Power BI project aimed at analyzing Zomato's sales data to provide actionable insights for the company's top management. The dashboard is structured into three interactive pages—Overview, User Analysis, and City Performance. Each page focuses on specific dimensions of Zomato’s business performance, integrating visualizations, KPIs, and data categorizations.

The project uses Power Query for data cleaning and transformation, and DAX (Data Analysis Expressions) to create insightful measures. The interactive nature of the dashboard helps stakeholders understand trends, identify strengths and weaknesses, and make data-driven decisions.

Dashboard Details

Page 1: Overview
Key Components:


Top City by Quantity Sold: A visualization that highlights the city with the highest quantity of items sold, categorized into Veg and Non-Veg.
Sales by Year: A line or bar chart showing the trend of total sales over multiple years.
KPIs:
Total Sale Amount: Aggregate sales revenue.
Total Orders: Total number of orders placed.
Total Rating: Combined user ratings of orders.
Categorization by Veg/Non-Veg: Segments sales, orders, and ratings into Veg and Non-Veg categories for deeper insights.
How It Helps Decision-Making:

By observing the Top City by Quantity Sold, management can allocate resources effectively, such as increasing delivery staff or marketing in high-performing cities.
The Sales by Year chart helps assess growth over time, enabling management to identify and replicate successful strategies in underperforming years.
The Veg vs. Non-Veg categorization provides insights into consumer preferences, aiding in inventory planning and targeted marketing campaigns.

Page 2: User Analysis

Key Components:

User Gained and Lost: Metrics showing the number of new users acquired and users who have churned.
Users by Age: A bar chart displaying the age distribution of Zomato’s user base, highlighting the dominant customer demographic.
KPIs:
Active Users: The number of currently active users out of the total registered users.
How It Helps Decision-Making:

Tracking Users Gained and Lost allows management to assess the effectiveness of marketing campaigns and retention strategies. For example, a high churn rate might indicate poor service quality or lack of loyalty programs.
The Users by Age chart enables management to design targeted campaigns, such as promotions for millennials if that demographic is dominant.
Understanding the Active Users metric helps identify the actual engagement level within the user base, guiding decisions on how to improve user retention.

Page 3: City Performance

Key Components:

Sales by City: A chart displaying the sales distribution across different cities.
Rating by City: Average user ratings for each city.
Users by City: The distribution of users (active and total) across cities.
City-Wise Table: A detailed table summarizing:
Sales
Orders
Gained Users
Lost Users
How It Helps Decision-Making:

The Sales by City visualization helps identify low-performing cities, enabling management to plan targeted sales drives or promotional activities in these areas.
Rating by City provides insights into customer satisfaction, which can guide service improvement initiatives.
The City-Wise Table offers a granular view, allowing management to compare cities on multiple dimensions and make data-driven investment decisions. For instance, if a city has high sales but low user acquisition, marketing efforts can focus on attracting new users in that area.
Technical Details
Data Preparation Using Power Query
Power Query was used to clean and prepare the dataset by:

Removing unnecessary columns: Reducing noise and focusing only on relevant data.
Adding new columns: Derived insights like Veg/Non-Veg categorization, year of sale, and user status (active/lost).
Creating new tables: For specific analyses, such as age groups or city-specific data.
Data Modeling and DAX
DAX measures were created for calculating:

Total Sales, Total Orders, and Total Ratings.
Active Users, Lost Users, and Gained Users.
Average ratings and sales per city.
Visualization
Visualizations were crafted using Power BI’s interactive charts, slicers, and tables to ensure stakeholders can drill down into specific metrics dynamically.

Impact and Business Decisions that can be made using the dashboard

The Zomato Sales Dashboard empowers top management with data-driven insights, such as:

Optimizing Menu Items:

If Veg items are outperforming Non-Veg, Zomato can invest in expanding its Veg offerings or focus marketing efforts on this segment.

Improving User Retention:

High churn rates flagged on the User Analysis page prompt the implementation of loyalty programs or subscription models to retain users.

Enhancing City Performance:

For cities with low sales but high user activity, targeted discounts or partnerships with local restaurants can drive sales.

Resource Allocation:

By identifying top-performing cities, management can allocate more delivery staff or invest in marketing campaigns to sustain growth in these areas.

Tracking Growth:

Yearly sales trends provide clarity on business growth and help set realistic targets for future periods.

Conclusion

The Zomato Sales Dashboard provides a unified view of the company’s performance across users, sales, and cities. By leveraging the interactive features of Power BI and advanced analytics using DAX, this project offers actionable insights, enabling the management to make informed, strategic decisions. The dashboard is a robust tool for monitoring, evaluating, and planning Zomato’s business operations.
