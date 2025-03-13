# Aircrash-Investigation-Analysis

## INTRODUCTION
Air travel is one of the means of transportation that various people around the world use to commute to different locations. This analysis aims to uncover patterns, trends, and key insights from historical air crashes using Microsoft Excel.

## RESEARCH QUESTIONS
*	What are the trends in air crashes over time?
*	Which countries/ regions have the highest number of crashes?
*	Which location is the deadliest in terms of casualties?
*	Which aircraft manufacturers have the highest number of casualties?
*	Airline operators with the highest number of casualties?
*	What is the average survival rate in air crashes?
*	What is the total number of air crashes, casualties, and people aboard?
*	What month of the year has the most crashes?
*	What is the total number of people that survived?
*	What quarter of the year has the most crashes?

## Analysis Steps
To solve this research question, the following analysis steps were taken:
1.	Data Cleaning/ Collection:
*	Retrieve the data set from online source’s (Kaggle) and import into Microsoft Excel
*	Fill/ remove records that are empty and remove duplicates  
*	Standardized data types for each of the columns
*	Created a new column for total causality using the sum of the fatalities (air) and ground columns
2.	Exploratory Data Analysis:
*	Created pivot tables to solve the research questions gotten
*	Filtered and sorted the pivot tables to fit my analysis
*	Calculated survival rate using
Survival Rate = ∑ Survivors / ∑ Aboard *100
	NB Survivors = Total Aboard – Total Causalities
*	Calculated total number of crashes using the total count of rows for any column:
i.e COUNT(A:A) for the year column

3.	Data Visualization
*	Created pivot charts of various types to visualize the pivot table initially created
*	Designed a suitable dashboard to show all my pivot tables, which makes it more visually appealing


 ## FINDINGS
1.	Overall Trends:
*	The highest number of air crashes occurred mostly towards the end of the year
*	The number of air crashes has reduced in the last four years over time due to improved safety measures
2.	Regional Trends:
*	In terms of deadliest country and country with the highest crashes Russia has the most
*	The most affected region tends to have the highest number of air traffic
3.	Aircraft & Operator Analysis
*	The operator with the most causalities and most crashes is Aeroflot
*	Aircraft manufactures Airbus and Boeing have been involved the most in terms of causalities
4.	Causalities Analysis
*	The average survival rate is 23% per crash
*	The deadliest region had about 8132 causalities
*	A total of 33,617 people survived in the air crashes
  
 ## CONCLUSION/ RECOMMENDATION
The air crash investigation analysis provides valuable insights into trends, factors contributing to aviation accidents. The study shows a decline in crash incidents, likely due to advancements in aviation technology and regulatory improvements. However, certain operators, aircraft manufacturers, and geographic regions exhibit higher crash frequencies, highlighting areas that may require further safety measures. Based off this some recommendations are provided below:
*	Operators should strengthen their safety measures most especially high-risk operators.
*	Aircraft manufacturer should improve aircraft maintenance and inspections for frequently involved aircraft models
*	Enhance safety awareness and training programs for pilots and airline staff.
*	Research should be conducted on weather to know the time of the year safe for flight



