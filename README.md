# Product and Customer Analysis
This my POWER BI where ,I have analysed data of a Product Based company(2020-2022). In brief ,I have used POWER QUERY to clean, format, merge, append data. I have used DATA MODELLING to connect more than 8 Tables using STAR and SNOWFLAKE SCHEMA. I have used DAX to create various measures and conditional columns to manipulate and get better understanding of goals.

DATASET DESCRIPTION-
Customer Lookup- This contains data about our customer's Name, email gender, background details etc and has Customer Key as a Primary Key.
Product Category- This is data is about our total number of product categories and has Product Category Key as a Primary Key.
Product Lookup- This contains data about our products. Howm many they are, Model number ,Cost ,Subcategory etc. It has Product Key as a primary Key and ProductSubcategoryKey as Foreign Key
Product Subcategory- This contains data about our subcategories and Product subcategory is Primary key and Product Category key as Foreign key
Returns - This contains data about our Returns, Return date, from where they have returned, return quantity. It has territory key and product key as a foreign key
Product Territory- It has information where our business runs(Countries,Regoins etc) and has Salest territory key as Primary key
Sales data - Their are 3 sheets of sales data 2020,2021,2022 it conatins about our order date, stock date, product key, territory key,quantity ordered
Calendar -Dates when business operated

POWER QUERY
Power query is used to clean data, finding errors, appending sales data, extracting year name, month name and much more date related data from calendar lookup sheet, formatting columns, extracting SKU type, clearing data redundacy, handling null values finding price after discount and much more backend related work.

DATA MODELLING -
For Data Modelling, I have used STAR and SNOWFLAKE SCHEMA to to create relationships and cardinality. For that You can chect my word file for data modelling.

DAX-
I have used DAX to Manipulate data and to find valuable understandings. I have created 30+ measures from different DAX formulas 
following are the DAX formulas, I used-
CALCULATE
SUM X
RELATED
COUNTDISTINCT
DATESINPERIOD
DATESADD
AVERAGE
SUM
DATESMTD
DATESYTD
CONDITIONAL IF STATEMENTS 
SWITCH
DIVIDE
COMBINING MEAURES ETC






