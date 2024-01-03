# Cohort-Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Results](#results)
  
### Prorject Overview
This analysis aims to identify patterns and trends in user behavior over time.

### Data Sources
Online Retail: This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. [Download here](https://archive.ics.uci.edu/dataset/352/online+retail)

### Tools
 • SQL: Data Cleaning and Analysis
 
 • PBI(PowerBi): Visualization

 ### Data Cleaning
 In the initial preperation phase, I perform following tasks:
 1. Load data.
 2. Handle missing data. Given that most of the missing values pertain to Customer_ID and are beyond adjustment, I opt to drop all null data.
 3. Remove duplicates.

 ### EDA (Explore Data Analysis) - (I won't perform this step in this analysis)
 I have already conducted exploratory data analysis (EDA) on the same dataset, [you can view the analysis here.](https://github.com/Huy24vt/RFM-Segmentation)

 ### Data Analysis
To perform basket analysis, we will need to caculate two things: Cohort Month, Period Cohort.
1. Cohort Month: refers to the month in which a group of users or customers is first identified or acquired.
   
2. Period Cohort: represent a group of users or customers who share a common characteristic based on the time elapsed since their last order.


### Results
 [You can view the dashboard here](https://app.powerbi.com/view?r=eyJrIjoiNWZjOTZlNGEtNmQzMS00ZmU1LWFhNGQtYTU4ZWI1ZDc5NGU0IiwidCI6IjJmODVkYzc0LWI2YjQtNDU4NC1iZWVlLWNjZGE3MTQ0NDk3MCIsImMiOjZ9)

<img width="356" alt="image" src="https://github.com/Huy24vt/Cohort-Analysis/assets/130732635/aae8370a-4eb0-4286-ae4b-b9b2cc2a8d91">

 
In conducting cohort analysis, businesses delve into the patterns and behaviors of user groups over specific time frames. This exploration allows them to uncover valuable insights into customer engagement and preferences. By identifying common characteristics within these cohorts, businesses can implement targeted strategies to enhance user satisfaction, optimize product offerings, and ultimately boost overall performance.
