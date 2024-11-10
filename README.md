# Ufood-Marketing-Analysis
This complete project is done using Google colaboratory(Python Programming Language)

1.0	UFOOD MARKETING ANALYSIS

1.1	DATA BACKGROUND

UFood is the lead food delivery app in Brazil, present in over a thousand cities. Keeping a high customer engagement is key to growing and consolidating the company’s position as the market leader. This marketing campaign data consists of information obtained from 6 different responses. The aim is to provide insights, define cause and effect provide a better understanding of the characteristic features of respondents; Propose and describe a customer segmentation based on customer behaviors; Visualize data, and provide written reasoning behind discoveries. A few of the research questions include; a. What is the most used means of making purchases? b. What's the Total number of accepted campaigns in the last two years and responses? c. What's the cor
relation analysis and time series analysis of the columns? d. Which customer demographics responded best? Python programming language is employed and a series of basic data analysis libraries e.g. pandas, matplotlib, and seaborn imported. 

1.2	DATA CLEANING AND PREPARATION	

  The following steps were taken in cleaning and preparing the data for analysis: 

•	Checking for null values in each of the 2205 rows and 38 columns of information.
•	Removing the duplicated values from the dataset
•	Combining the five different columns of marital status as one and removing the duplicates
•	Repeating step three for the children's column
•	A new column total campaigns created by joining the accepted campaigns by each household into one as well as their respective educational background

1.3	EXPLORATORY DATA ANALYSIS
	
 These were the steps employed in exploring the data, deriving information using different samples of it to gain insights and construct models:

•	A correlation model using heatmap is visualized between the numerical columns and also between the total accepted campaigns and the numerical data
•	A pointplot showing age groups and total accepted campaigns for each
•	The percentage of total accepted campaigns by age group is also represented using a barplot
•	The entire data was trimmed into 523 rows out of 2204 rows as some customers have zero number of accepted campaign
•	A barplot representing the total amount spent by different age groups compared with amounts spent by age groups of those who only accepted
•	The total amount spent using different payment methods was also accessed between accepted and rejected campaigners
•	Multiple linear regression models were made between Payment methods, number of children, total campaigns, educational status, marital status, and total amount spent.

1.4	DATA INTERPRETATION 
  
  The following inferences, observations, and insights were obtained from the complete analysis of the ufood marketing dataset:

•	The marketing campaign as a whole has a minimal response rate of 23%
•	There is a positive correlation between those who accepted the campaigns and spending on wines and regular products which should be specially targeted demographics for future campaigns
•	Customers between the age groups 41-50 and 23-30 have the max and min percentage response to the different campaigns run. This implies that the younger generation finds the idea of answering campaigns unappealing which could be worked on and improved on in future campaigns
•	Coincidentally, the highest amount of purchases for those that accepted and in total lies in the 41-50 age groups (approx. 30,000). This amount can serve as a target to improve on in future campaigns
•	The total amount comparison between the purchase methods is Store > Web > Catalog
•	Regression models show the following trends: (a) Total amount –  Number of children has a negative relationship (b) Total campaigns – Number of children has a negative relationship (c) Graduated and married customers – Total amount spent has a positive relationship
