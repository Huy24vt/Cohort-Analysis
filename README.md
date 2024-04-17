# Cohort-Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Results](#results)
  
### Prorject Overview
The primary objective of this analysis is to delve into the intricate patterns and evolving trends within user behavior over time. By leveraging advanced analytics techniques and robust data mining methodologies, we seek to uncover actionable insights that illuminate the dynamics of user interactions with our product/service offerings.

This comprehensive analysis will encompass a wide array of user behavior metrics, spanning from usage patterns and engagement metrics to purchase behavior and customer segmentation. Through a meticulous examination of historical data sets, we aim to discern meaningful patterns and discernible trends that may offer valuable strategic insights.

<img width="410" alt="image" src="https://github.com/Huy24vt/Cohort-Analysis/assets/130732635/f73878bb-41b0-49b3-acd8-fdc3c51684f5">


Key components of this analysis include:

1. Usage Patterns and Session Dynamics: Explore how users engage with our platform/service over time. Analyze usage patterns, session duration, and frequency of interactions to identify trends in user engagement and product/service utilization.

2. Purchase Behavior and Transactional Insights: Investigate patterns in purchase behavior, including frequency of transactions, average order value, and product preferences. By dissecting transactional data, we aim to uncover purchasing trends, response to promotional activities, and shifts in consumer preferences.

### Data Sources
Online Retail: This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. [Source here](https://archive.ics.uci.edu/dataset/352/online+retail)

### Tools
 • SQL: Data Cleaning and Analysis
 
 • PBI(PowerBi): Visualization

 ### Data Cleaning
 In the initial preperation phase, I perform following tasks:
 1. Load data.
 2. Handle missing data. Given that most of the missing values pertain to Customer_ID and are beyond adjustment, I opt to drop all null data.
 3. Remove duplicates.

 ### EDA (Explore Data Analysis)
 Exploratory Data Analysis (EDA) involves delving into sales data to uncover insights and answer key questions that can inform business decisions. Here are a few key questions:

 - What is the overall sales?
   
<img width="336" alt="image" src="https://github.com/Huy24vt/RFM-Segmentation/assets/130732635/61671bad-2104-4da4-91c4-467346656d74">

 - How do sales vary on a weekly and monthly basis?
 - How do sales vary on an hourly basis?

<img width="389" alt="image" src="https://github.com/Huy24vt/RFM-Segmentation/assets/130732635/e8caf20a-a4ab-4372-9459-5cc74ca3dadd">

   
 - Which days of the week have the highest sales performance?

<img width="401" alt="image" src="https://github.com/Huy24vt/RFM-Segmentation/assets/130732635/ddef3ccc-af2d-4ef5-80e9-b09fcec51703">

 ### Data Analysis
To conduct basket analysis effectively, we will employ two key metrics: Cohort Month and Period Cohort. These metrics play a crucial role in understanding customer behavior and segmentation, enabling us to derive actionable insights for improving business strategies and operations.

1. Cohort Month: This metric refers to the month in which a group of users or customers is first identified or acquired. Cohort analysis involves grouping customers based on their initial interaction or acquisition date, allowing us to track their behavior and engagement over time. By identifying the cohort month, we can analyze how customer behavior and purchasing patterns evolve from the point of acquisition. This insight is invaluable for understanding customer retention, lifetime value, and the effectiveness of marketing and acquisition efforts over different time periods.

2. Period Cohort: Period cohorts represent groups of users or customers who share a common characteristic based on the time elapsed since their last order. This metric enables us to segment customers based on their recency of purchase, providing insights into their purchasing frequency and loyalty. By categorizing customers into period cohorts, such as recent purchasers, frequent purchasers, or lapsed purchasers, we can tailor marketing strategies and retention efforts to effectively target each segment. Moreover, period cohort analysis allows us to identify trends and patterns in customer behavior over time, helping us anticipate future purchasing trends and adapt our strategies accordingly.


### Results
 [You can view the dashboard here](https://app.powerbi.com/view?r=eyJrIjoiNWZjOTZlNGEtNmQzMS00ZmU1LWFhNGQtYTU4ZWI1ZDc5NGU0IiwidCI6IjJmODVkYzc0LWI2YjQtNDU4NC1iZWVlLWNjZGE3MTQ0NDk3MCIsImMiOjZ9)

<img width="356" alt="image" src="https://github.com/Huy24vt/Cohort-Analysis/assets/130732635/aae8370a-4eb0-4286-ae4b-b9b2cc2a8d91">

 
In the process of conducting cohort analysis, businesses undertake a detailed exploration of the patterns and behaviors exhibited by user groups over specific time frames. This meticulous examination allows businesses to uncover nuanced insights into customer engagement, purchasing behaviors, and preferences. By systematically grouping customers into cohorts based on common characteristics such as acquisition date, demographics, or behavioral traits, businesses gain a deeper understanding of how different segments interact with their products or services over time.

<img width="405" alt="image" src="https://github.com/Huy24vt/Cohort-Analysis/assets/130732635/ed580ab2-ffa6-4168-bb44-8debab42f1bb">


Looking at this trend in old-new customers, we have some key points to consider:

1. Market Saturation: A decrease in new customers could indicate market saturation or decreased demand for the product or service. It's important to assess whether the market is becoming saturated and if there are diminishing opportunities to attract new customers.

2. Customer Loyalty: An increase in the number of old customers suggests higher customer retention and loyalty. This could be attributed to factors such as superior product quality, excellent customer service, or effective loyalty programs. It's crucial to understand what is driving customer loyalty and capitalize on it to maintain and strengthen relationships with existing customers.

3. Competitive Landscape: Changes in the competitive landscape may impact customer acquisition and retention. Increased competition or the entrance of new competitors could make it more challenging to attract new customers, while also incentivizing businesses to focus on retaining existing customers through differentiated offerings and superior customer experiences.

4. Marketing Effectiveness: Analyzing the effectiveness of marketing efforts is crucial. A decrease in new customers could be indicative of ineffective marketing strategies or channels. It's essential to evaluate marketing campaigns, messaging, and channels to identify areas for improvement and reallocate resources effectively.
