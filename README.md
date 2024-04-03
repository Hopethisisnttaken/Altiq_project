# AltiQ Hardware Financial Analysis (Final Project for Tripleten)


### Table of contents:
- [Project overview](#project-overview)
- [Data sources](#data-sources)
- [Tools](#tools)
- [Exploratory data analysis](#exploratory-data-analysis)
- [Key findings](#key-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)


### Project overview:

<img width="699" alt="Screenshot 2024-04-03 at 22 58 27" src="https://github.com/Hopethisisnttaken/finance_for_T10/assets/151781214/ea297b21-93fe-4e45-867c-202cc4a00f9d">


The purpose of this project is to provide financial overview, insights and future advice for AltiQ Hardware.
The data used is from September 2017 to December 2021, and so all the insights, assumptions and overview regard the data from that time peroid alone. 

[Link to Tableau final report](https://public.tableau.com/app/profile/omri.meir/viz/finalprojectdashboard_17102352479540/Dashboard1)

 ### Data sources: 

The dataset used for this analysis is within the "altiq_db.sqlite3" file. It contains 6 dataframes: 
  1. dim_customer -contains customer-related data
  2. dim_product -contains product-related data
  3. fact_pre_discount -contains pre-invoice deductions information for each product
  4. fact_manufacturing_cost -contains the cost incurred in the production of each product
  5. fact_gross_price -contains gross price information for each product
  6. fact_sales_monthly -contains monthly sales data for each product.

### Tools:

- SQL server - queries for relevant data
- Jupyter Notebook - Exploratory data analysis
- Tableau - Creating a final report


### Exploratory data analysis:

the EDA involoved exploring the data to answer key questions in several topics:
  1. Do revenue and gross profit increase yearly?
  2. What are the most and least profitable months? 
  3. What does an average customer look like?
  4. Which product categories are the most profitable?
  5. Which sales platforms are more profitable?


### Key findings:

- Revenue and gross profit are increasing yearly. 2022 is the most succesful year yet. 
- Months October to February have the highest average revenue and profit, March to Septmber have low revenue and profit. December has the highest values while March has the lowest.
- APAC is the region with highest average revenue per customer, followed by NA. 
- Internal HDD is the highest sold category across all regions.
- Customers from NA buy in larger quantites when they buy via the E- Commerce platform

### Recommendations:

Based on the analysis I recommend the following actions:
- Marketing efforts should be taken to increase sales between March to September.
- In LATAM marketing efforts should be directed towards aquiring a larger customer base.
- Focus on promoting products on E-commerce platforms.

 ### Limitations:

1. There are data on only two categories of sold producets, so the insights provided will only regard the data that is provdied.
2. 2022 (fiscal year) has only four months of data, which have been excluded from some of the analysis as they were extreme values (further explantion within the notebook)
3. The analysis and recommendations are based soley on the data provided from said dates. 



  
