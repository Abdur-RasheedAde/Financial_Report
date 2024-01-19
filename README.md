# Haut  Supermarket Sales Report (2013 and 2014)

![Slide1](https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Slide1.PNG)

##  Introduction
This is a Power BI project on sales analysis of an hypothetic Supermarket, Haut Super market for 2 consecutive years (2013 and 2014). The project is to clean, analyze and draw insights in order to answer some critical question and help stake holders of Haut make informed decisions.


## Data Source:
The data used in this project is a modified microsoft dataset known as Financial Samples;  
* Microsoft Financial Sample Data [DownloadMicrosoftData](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download)
* Modified Dataset used in this Project [DownloadModifiedDataset](https://docs.google.com/spreadsheets/u/2/d/1xkWC6Jlk_YZECHbpUtoc8AEiPb9jfcld/edit?usp=drive_web&ouid=114068862415751566917&rtpof=true)

## Problem Statement
This project is aimed at improving business performance of Haut supermarket and hence, answer the following questions;
1. What is the monthly trend of total sales?
2. What is the revenue performace compare to same period last year?
3. What is the profit ratio on quarterly basis?
4. Which products are the most and least profitable?
5. Which sales regions are the most and least profitable?
6. Does discount has an effect on Sales?
7. Does season of the year has an influence on sales?
8. What is the performance of the Africa market relative to other continent?
9. Which country is most profitable?
10. Which provinec is the most performing with total sales?

## Power BI and Analytics Technical Skills:
+ Project Planning and Documentation
+ Data Gathering
+ Power Query
+ Data Modelling
+ Report Design
+ Data Visualization
+ Data Analysis Expression (DAX)
+ Page Navigation and Button
+ Business and Analytics Reporting
+ Performance Optimization
+ Scalability
+ Feedback and Continuous Improvement
  
## Data Modelling
To optimize the performance of the data model, a calendar table was created using the DAX function. The data model follows a star schema with one fact table and three dimension tables. The dimension tables have PRIMARY KEYS that connect to the corresponding FOREIGN KEYS in the fact table, forming a one-to-many relationship between each dimension table and the fact table. The diagram below shows the data model.
<img src="https://github.com/Abdur-RasheedAde/Financial_Report/blob/main/Data%20Modelling.PNG" width=50% height=50%>
