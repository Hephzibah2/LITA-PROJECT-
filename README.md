# LITA-PROJECT-
To show all that I have learned from Ladies in Tech Africa (LITA), The incubator Hub 

### PROJECT TITLE: 
LITA CAPSTONE DATASET

### PROJECT OVERVIEW
This Data Analysis is to show key insights in the Sales Performance of a company

### DATA SOURCES
The Primary source of data used is LITA Capstone Dataset.xlsx

### TOOLS USED
- Microsoft Excel [Download here](www.micosoft.com)
1. For Data cleaning
2. For Analysis
- SQL- Structured Query Language: For querying data
- Power BI [Download here](www.microsoft.com)
1. For Data visualisation
- Github: Portfolio building

### DATA CLEANING AND PREPARATION
I performed the following actions
1. Data inspection
2. Handling missing variables
3. Data cleaning and formatting

### EXPLORATORY DATA ANALYSIS
1. What are the total sales for each product?
2. What is sum of sales for each region?
3. What are the sales of the company per month?

### DATA ANALYSIS
 This is where I talk about the functions and codes I used
 - E.g
   ''' SQL
   ----Monthly sales for current year----
select month ([OrderDate]) as [Sales Month],
       SUM([sales]) as [Total Sales]
	   from [dbo].[Sales data]
	   where year([OrderDate])='2024'
	   group by month([OrderDate])
	   order by 1
'''
