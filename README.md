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
  '''  SQL
select month ([OrderDate]) as [Sales Month],
       SUM([sales]) as [Total Sales]
	   from [dbo].[Sales data]
	   where year([OrderDate])='2024'
	   group by month([OrderDate])
	   order by 1
''' 

### DATA SUMMARY
 I used Microsoft Excel to give summary of my data
 1. Total Sales by Product
 https://github.com/Hephzibah2/LITA-PROJECT-/blob/main/223f4819-c6e9-42fd-b035-e3e2b3b2cd31%20Copy.jpeg

2. Total Sales by Region
   https://github.com/Hephzibah2/LITA-PROJECT-/blob/main/223f4819-c6e9-42fd-b035-e3e2b3b2cd31%20Copy.jpeg

3. Total Sales by Month
   https://github.com/Hephzibah2/LITA-PROJECT-/blob/main/223f4819-c6e9-42fd-b035-e3e2b3b2cd31%20Copy.jpeg
   
5. Top Selling Product
6. Average Sales per Product
