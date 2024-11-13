# FINANCE_ETL_PROJECT

By: Bidyashree Aditya, Arpit Sharma, Sakshi Kumari, Pankil Kambhoj


![th](https://github.com/user-attachments/assets/7368ca3c-6a9a-4a24-ac4c-c846a878963d)



#PRODUCT SALES ANALYSIS USING A FINANCIAL DATA WITH ETL ( EXTRACTING, TRANSFORM, LOADING) WITH DATA VISUALIZATION.

#Introduction

In business, the analysis of product sales data plays a strong role in understanding product dynamics, identifying trends, and making informed data-driven decisions. The dataset we will be using here has a comprehensive record of key variables related to product sales, providing a valuable resource for uncovering insights from it.

#It comprises essential columns such as:
Segment
Country
Product
Discount Band
Units Sold
Manufacturing Price
Sale Price
Gross Sales
Discounts
Sales
Cost of Goods Sold (COGS)
Profit
(Date, Month Number, Month Name, and Year.) 


 #---->>>>>>>This analysis aims to extract meaningful insights and trends in product sales.

Tools used: SNOWFLAKE FOR DBT, JUPYTER, PANDAS


![snowflake](https://github.com/user-attachments/assets/bfea8681-e0cc-42e1-92fd-48e8d86dccc0)

Methodology: 

1->First we are cleaning the data, as dataset was having null values . We converted it to 0 using pandas.

2->Now, the cleaned dataframe is uploaded to snowflake.

3-> A: The data will be transformed by using DBT tool. 
      
   -It is a very powerful SQL-based tool that helps Snowflake users manage
   -data transformations, 
   -streamline ETL workflows,
   -enforce data quality
   
   This fast and scalable data transformation framework, making Snowflake data more accessible, consistent, and analysis-ready for the business.

   B: DBT promotes a modular structure for SQL transformations by breaking down complex transformations into manageable, reusable "models" (SQL files).
  
   -> Imp** : In DBT, each model typically represents a SQL query that builds or updates a table or view in Snowflake.


   


   ![Screenshot 2024-11-13 005859](https://github.com/user-attachments/assets/a8ea6574-757b-437d-acc6-6021c91f43b3)

   ---->>>> dbt init, dbt debug, dbt run 

   
   ![Screenshot 2024-11-13 010945](https://github.com/user-attachments/assets/4e00936c-d4b0-4a9b-9872-8f1c36b69998)


4-> Now the data is tranformed it will be loaded to the Jupyter with the help of functions.

5-> At last the visualizations are from this Loaded file of the Jupyter using MATPLOTLIB , converted to pdf (matplotlib backends PdfPages) and send an email of this pdf (MIMEText, MIMEMultipart)



--------------------------------------------------------------------------------The end-------------------------------------------------------------------------------------------------------------------------









 


 
