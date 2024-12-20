## Project Overview

This project focus on analyzing call center data to uncover trends in calls volumes, customer sentiment, and response time performance across various channels, states, and call reasons. By leveraging the dataset, the analysis aims to identify operational in SLA compliance, and enhance customer satisfaction. 

## Introduction

This report analyzes cell canter data to identify trends in call volumes, sentiment, response times, and performance across various channels, states, and reasons. Insights aim to improve customer satisfaction, optimize resources, and address operational gaps.

## Problem statement

The call center receives varying call volumes across channels, states, and sentiments. The goal is to analyze the key performance metrics to:

1.	Identify reasons for high call volumes.
2.	Assess response time compliance (Within SLA vs. Below SLA).
3.	Analyze customer sentiment across various states and channels.
   
#### Key Insights

- Show Total Call for the month
- Show the Total call duration in minutes
- Show the Total call duration in hours
- Show the Average call duration
- Show the Total calls by Day
- Show the Total calls by State
- Show the Total calls by Reason
- Show the Total calls by Channel
- Show the Total Calls by Sentiments
- Show the Total Calls by Call-Centers

## Data Sourcing  
Data was provided online in Excel format. I downloaded the CSV file and imported it into Power BI for cleaning, analysis, and visualization, including; Call timestamps, Call duration and volume, State, Channel, Reasons for calls, Response time, SLA compliance and Sentiment scores.

## Power BI Concepts Applied 
The following Power BI concepts were applied to build the dashboard:
Data Import
Calculated column
Data Modelling
Data Visualization
Slicing and Filtering
DAX Measures

## Data Cleaning 
-	Removed duplicates and null values.
-	Making first row as headers.
-	Created new column for date from the Call Timestamp.
-	Standardized call reasons, states, and channels for consistency.

  ![image](https://github.com/user-attachments/assets/ea9b59fc-9125-4091-8d47-e6f74162fbc4)

 ## Data Analyzing and Visualization
 
-	Key metrics (e.g., total calls, duration, sentiment trends) were calculated using DAX formulas. 

-	Visuals to identify patterns:
  
	Calls by Day, State, and Channel.

	Sentiment Analysis.

	Response Time and SLA compliance.

-	 Some measures were added to help in the analysis. Which are shown below;

#### Total call duration in Hours

![image](https://github.com/user-attachments/assets/a2439c11-65cf-4101-ab24-65640ed90f9f)

#### Total call duration in Minutes

![image](https://github.com/user-attachments/assets/0b2c2167-7a8a-4e81-a489-f02bcf539dfe)

#### Average call duration

![image](https://github.com/user-attachments/assets/b593aeee-a9db-4733-80c6-8dd4828c820d)


#### Below is the Dashboard I created

![image](https://github.com/user-attachments/assets/22e86a0b-bb43-4a27-84b0-b4d8a9bddebc)


#### From The Dashboard, It Is Observed That;

#### The Total Calls for the Month = is 32941

![image](https://github.com/user-attachments/assets/478af64f-29ff-42e0-b9f3-e3fc90ae7332)

#### Total Call Duration for the Month in Minutes is = 824222

#### Total Call Duration for the Month in Hours is = 13,737

#### Average Call Duration is = 25

#### Response time (%) is = 62.6%

#### Show Total Call by Day

#### Show Total Call by State






