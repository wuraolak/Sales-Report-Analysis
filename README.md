# Sales Report Analysis

## Introduction
In today’s highly competitive business environment, understanding sales performance is crucial for driving growth and achieving strategic objectives. This sales report analysis provides a comprehensive assessment of the sales performance and identifies trends, opportunities, and challenges that have emerged during this period.

## Objectives
- Analyze sales data to identify trends.
- Calculate key performance metrics. 
- Visualize sales performance across various dimensions (e.g product category, region) in order to inform business strategies and decision making.

## Tools Used

### Excel
 - Data Cleaning and Calculations
 - Creating pivot tables for trend analysis.

### SQL
- Writing queries to extract and manipulate data.

### Power BI
- Visualizing data and generating interactive dashboards.

-------

## Data Cleaning with Excel and Excel formulas used                 

**Steps:**

- Removing Duplicates: Used the “Remove Duplicates” feature to clean the dataset to ensure accuracy.

- Data Formating: Ensured consistent date formats were used. MM/DD/YYYY for consistency in analysis.
  
**Formulas Used:**

- SUM
- AVERAGEIF
- SUMIF

**Calculations in Excel:**

**1. Total Sales Calculations:**
- Calculated revenue using (Quantity * UnitPrice) and used the fastfill method to fill all the way down
- Calculated total sales(Revenue) using the formula
  
                   =SUM(H2:H9922)
 which resulted in a total revenue of **2,101,090**

 ------

 **2. Average Sales per Product:**

- Calculated the average sale per product using
  
                  =AVERAGEIF(C2:C9922, "Shirt", H2:H9922)
 yielding an average of:
 
  **Shirt** 326.56, **Shoe** 308.70,  **Hat** 158.81, **Socks** 121.82, **Jacket** 139.94, **Gloves** 200.07.

  ----------

**3.Total Revenue by Region:**

- Calculated total revenue for each region using
  
                  =SUMIF(D2:D9922, "North", H2:H9922) 
and the fast fill method to fill down which resulted to the totals for;

**North** = 387,000, **South** = 927,820, **West** = 300,345, **East** = 485,925

-------
 
## Pivot Tables in Excel

- Created a pivot table to analyze sales by region, products and month, providing insights into geographical performance.
  
  **Visuals:**













