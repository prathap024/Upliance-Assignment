# Upliance-Assignment
Analysis of User Behavior, Cooking Preferences, and Order Trends


Overview
This assignment focuses on analyzing datasets related to user behavior, cooking preferences, and order trends. The analysis involves data cleaning, merging, exploration of relationships, and creating visualizations to derive actionable insights. The findings are summarized to assist business decision-making.

Objectives
1.	Data Cleaning & Preparation: Ensure datasets are consistent, clean, and ready for analysis.
2.	Data Merging: Combine the datasets into a unified structure.
3.	Analysis:
  o	Explore the relationship between cooking sessions and user orders.
  o	Identify popular dishes.
  o	Investigate demographic factors influencing user behavior.
4.	Visualization: Use visualizations to highlight key trends and insights.
5.	Reporting: Summarize findings and provide business recommendations.

Datasets
1.	User Details: Contains demographic information such as User ID, Age, Gender, and Location.
2.	Cooking Sessions: Details about cooking sessions, including Session ID, User ID, and session-related metrics.
3.	Order Details: Information about orders, including Order ID, User ID, Dish Name, Dish Category, and Order Time.

Steps Performed
1. Data Cleaning
•	Checked for null values, duplicates, and inconsistencies.
•	Converted data types for easier analysis (e.g., dates, categorical variables).
2. Data Merging
•	Merged datasets using User ID to create a unified Data frame.
3. Exploratory Data Analysis
•	Analyzed the relationship between cooking sessions and user orders.
•	Identified popular dishes based on order frequency.
•	Explored demographic factors, such as age and, influencing user behaviour.
4. Visualizations
•	Created bar charts, pie charts, and line plots to highlight key insights:
o	Popular Dishes: Top 10 dishes by order volume.
o	Age Group Analysis: Total sessions and average orders per session by age group.
o	Location Trends: Orders by location.
o	Time of Day: Peak hours for placing orders.
5. Reporting
•	Key findings and business recommendations are summarized in the final report.

Key Insights
1.	Popular Dishes:
o	The most popular dish had significantly higher orders compared to others.
o	Dessert categories were highly favored.
2.	Demographic Trends:
o	The age group 25-34 had the highest engagement and order volume.
o	Gender trends showed slightly higher participation from females in cooking sessions.
3.	Time Trends:
o	Peak order times were observed during dinner hours.
4.	Location:
o	Urban regions contributed to the majority of orders, highlighting key markets.

Business Recommendations
1.	Menu Optimization:
o	Focus on promoting popular dishes and improving availability.
2.	Targeted Marketing:
o	Run marketing campaigns tailored to the 25-34 age group and urban locations.
3.	Operational Efficiency:
o	Prepare for high order volumes during peak hours by optimizing staff and resources.
4.	New Opportunities:
o	Explore less popular age groups and regions for growth opportunities.

Technologies Used
•	Python: For data cleaning, merging, and analysis.
    o	Libraries: pandas, numpy, matplotlib, seaborn
•	Jupyter Notebook: For documenting and executing the analysis.
•	GitHub: To host the project repository.

How to Run the Code
1.	Navigate to the project directory.
2.	Open the Jupyter Notebook: jupyter notebook Assignment_analysis.ipynb
3.	Follow the steps in the notebook to reproduce the analysis and visualizations.

