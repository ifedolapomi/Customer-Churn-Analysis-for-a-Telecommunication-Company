# Customer-Churn-Analysis-for-a-Telecommunication-Company
Objective:
Analyze the provided customer data to identify factors contributing to customer churn and develop strategies to improve retention.

Steps:
Data Import and Cleaning:

Import the dataset into Excel.
Check for and handle missing values.
Ensure data types are correct (e.g., numerical values for income, overage minutes, etc.).
Remove duplicates and correct any inconsistencies.

Descriptive Statistics:

Calculate summary statistics (mean, median, standard deviation) for numerical columns like INCOME, OVERAGE, LEFTOVER, HOUSE, HANDSET_PRICE, OVER_15MINS_CALLS_PER_MONTH, AVERAGE_CALL_DURATION.
Create frequency tables for categorical variables like COLLEGE, REPORTED_SATISFACTION, REPORTED_USAGE_LEVEL, and CONSIDERING_CHANGE_OF_PLAN.

Churn Rate Calculation:

Calculate the churn rate by dividing the number of customers who left (LEAVE = "LEAVE") by the total number of customers.
Create a pivot table to display churn rates by different segments, such as college degree (COLLEGE), reported satisfaction (REPORTED_SATISFACTION), and considering change of plan (CONSIDERING_CHANGE_OF_PLAN).
Exploratory Data Analysis (EDA):

Demographic Analysis:
Use pivot tables to analyze churn rates by COLLEGE and INCOME levels.
Create bar charts to visualize churn rates across different demographic segments.
Service Usage Analysis:
Analyze the relationship between OVERAGE, LEFTOVER, OVER_15MINS_CALLS_PER_MONTH, AVERAGE_CALL_DURATION, and churn.
Create scatter plots to visualize correlations between usage patterns and churn.
Customer Satisfaction and Usage Level:
Create bar charts to visualize churn rates by REPORTED_SATISFACTION and REPORTED_USAGE_LEVEL.
Considering Change of Plan:
Analyze how the consideration of changing plans (CONSIDERING_CHANGE_OF_PLAN) correlates with churn.
Create pie charts to show the distribution of customers considering changing their plans.
