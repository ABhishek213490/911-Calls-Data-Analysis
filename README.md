# 911-Calls-Data-Analysis

# 911 Calls Data Analysis

## Project Description
This project involves analyzing a dataset of 911 emergency calls to extract insights into emergency response services. The dataset comprises information such as the type of emergency, location, timestamp, and other pertinent details associated with each call. Through this analysis, we aim to discern patterns, trends, and factors influencing emergency calls to enhance emergency response systems and services.

## Objectives
1. Identify common types of emergencies reported in the dataset.
2. Analyze the distribution of emergency calls across different locations and time periods.
3. Investigate factors influencing the frequency and severity of emergency calls.
4. Explore correlations between emergency call characteristics and response times.
5. Provide actionable insights to enhance emergency response services and resource allocation.

## Problem Statement
Emergency response agencies need to efficiently allocate resources and prioritize emergency calls to ensure timely and effective assistance. By analyzing 911 call data, we aim to identify key factors affecting emergency call volume, response times, and resource utilization. This will help in improving emergency response strategies and optimizing service delivery to better serve the community.

## Approach
1. **Data Collection:** Obtain the 911 call dataset from reliable sources.
2. **Data Preprocessing:** Clean and preprocess the dataset to handle missing values, outliers, and inconsistencies.
3. **Exploratory Data Analysis (EDA):** Analyze the dataset using descriptive statistics, visualizations, and correlation analyses to identify patterns and trends.
4. **Statistical Modeling:** Apply statistical and machine learning techniques to explore relationships between variables and predict emergency call outcomes if applicable.
5. **Interpretation and Reporting:** Summarize findings, insights, and recommendations derived from the analysis in a clear and concise manner.

## Exploratory Data Analysis (EDA)
1. Distribution of emergency call types.
2. Geospatial analysis of call locations.
3. Temporal analysis of call volume by day, month, and time of day.
4. Correlation analysis between call characteristics (e.g., type of emergency, location) and response times.
5. Comparison of emergency call patterns across different demographic factors if applicable.

## Findings

Common types of emergencies reported:

To identify common types of emergencies reported, you can analyze the title column. Count the occurrences of different titles to find the most common types.
Top 5 towns and zip codes for 911 calls:

![Capture1](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/2d2cd275-d85a-44ff-8f79-3df3e79bc7a8)


Group the data by town and zip code, then count the number of 911 calls for each group. Sort the results to find the top 5 towns and zip codes with the highest number of calls.
Number of unique title codes:

You can create a new column based on the patterns in the title column, categorizing calls into broader reasons such as medical emergencies, traffic accidents, or fire incidents.
Most common reason for a 911 call:
![Capture3](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/4e07a731-2468-42b8-8158-d532915b504e)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/57309836-1ba2-4791-9fd7-08666379f75a)


After creating the new column, you can analyze it to find the most common reason for a 911 call.

Change the datatype of timestamp to datetime:

Convert the timeStamp column to datetime datatype for easier manipulation of date and time information.
Creating new columns related to datetime:
Extract additional features like month, year, day of the week, and hour from the timeStamp column to gain insights into the temporal patterns of 911 calls.
![Capture4](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/28c00f68-3a2e-4fcd-8cbd-b892c568b6d8)


Simple plot indicating the count of calls per month and day of week:
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/464430b9-ebda-49a5-84a2-aa2a02ef7eba)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/5b97ae50-61b4-4788-b4e8-04ba8b12163c)



Plot the count of calls per month to visualize the trend of 911 calls over time. Similarly, analyze calls vs. day of the week and calls vs. months.
Number of calls fluctuation by year and separate category reason for call by year:
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/1e7d4c07-328b-40f9-add0-dd5b7f7fb52d)


Analyze the number of calls over the years and break it down by the reason for the call to identify any trends or fluctuations.
Number of calls by day of the week and hour:
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/ee5df551-4f74-485b-b419-fbfb09ac7756)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/abbaa26e-2796-4d1e-8a68-6a8552fcf5c3)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/c702af2f-ac12-4bbf-a8aa-4a9d8c64526d)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/0b8e8f45-aeb2-43ec-8001-7ed93aae5698)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/2b4e621b-9e05-437d-801d-f09eb454d082)


Heat Map of number of calls by day of the week and hour:
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/b4f154a2-49df-44a1-b049-537ca267bfc8)


Clustermap and Heat map of Hourly calls by day of the week:
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/190af5ff-7264-4658-bcf5-b5a71e78c0b6)
![image](https://github.com/ABhishek213490/911-Calls-Data-Analysis/assets/161066148/e958df38-d5c


## Conclusion
Through comprehensive analysis of 911 call data, valuable insights have been gained into emergency call patterns, response times, and resource utilization. These findings can inform decision-making processes and strategies aimed at enhancing emergency response services, optimizing resource allocation, and ultimately improving public safety and well-being. Further research and collaboration with relevant stakeholders are recommended to implement actionable recommendations derived from this analysis effectively.
