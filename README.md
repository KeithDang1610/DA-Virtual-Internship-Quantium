# DA-Virtual-Internship-Quantium
During my Virtual Internship at Quantium Company, I gained valuable skills in data analysis, hypothesis testing, and data visualization using the R programming language. I worked on various tasks that enhanced my ability to analyze complex datasets
## Project Objectives:
- Analyze transaction and customer data to identify trends and inconsistencies. 
- Develop metrics and examine sales drivers to gain insights into overall sales performance. 
- Create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.
## Method Used:
- Data cleaning
- Data analysis
- Data Visualization
- Statistics
## Tools Used:
- R Studio
- R programming
## Library used:
- data.table
- ggplot2
- ggmosaic
- readr
- dplyr
## Datasets:
Including two tables 
Transaction data
![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/62d1c23a-ff0d-4b99-988a-7cb198dc7097)

Customer data
![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/de708551-4bd6-43da-a18d-357b85449ab4)

## Step-by-step:
### Exploratory data analysis
The first step in any analysis is to first understand the data. Let’s take a look at each of the
datasets provided.
#### Examining transaction data and customer data
- Using str() or glimpse() or skim_without_chart() to look at the format of each column and see the sample of the data.
- Using typeof() or summary() to check the type of values in columns
- Using summary() to find N/A values, and see the general stats with median, min, max, and mode.

![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/b34e59a1-9e53-4509-8b7e-0cc7b73f1eec)
We can see that there is an increase in purchases in December and a break in late December. and that there are zero sales on Christmas day itself. This is due to shops being closed on Christmas day.
#### After examining, and cleaning these datasets. Let's perform data analysis on customer segments:
Now that the data is ready for analysis, we can define some metrics of interest to the client:
- Who spends the most on chips (total sales), describing customers by lifestage and how premium their general purchasing behaviour is
- How many customers are in each segment
- How many chips are bought per customer by segment
- What’s the average chip price by customer segment
##### Who spends the most on chips (total sales)
![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/51fa41d7-f25c-44ae-8da2-a0fb28c3c5dc)
![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/edcede4b-f4ec-4a99-8ed4-dd0f3641a6f7)
-> Sales are coming mainly from Budget - older families, Mainstream - young singles/couples, and Mainstream - retirees

![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/e8cdd971-36fe-4b2d-8bb9-bc4fdcc72647)

-> There are more Mainstream - young singles/couples and Mainstream - retirees who buy chips. This contributes to there being more sales to these customer segments but this is not a major driver for the Budget - Older families segment.

![image](https://github.com/KeithDang1610/DA-Virtual-Internship-Quantium-Part1/assets/167521177/8b78570d-7a09-463f-8230-4ab4df51194e)
->Older families and young families in general buy more chips per customer

