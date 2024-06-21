
# Inventory Management System




## About

We are analysing Inventory analysis data that helps a company understand how to fill customer orders while keeping inventory costs low. The primary objective of Inventory Management is to ensure that you have enough stock or inventory of raw materials, components, parts and finished products to meet customer demand.
 

## Purpose Of the Project
The main goal of this project is to help businesses easily and efficiently manage the ordering, stocking, storing, and using of inventory. 



## Data Dictionaries

#### Table 1 tblcustomer




| Column | DataType     | Description                |
| :-------- | :------- | :------------------------- |
| Customer_id | INT| Customer ID number |
| First_Name |Varchar(40)|First Name of Customer|    
|Last_Name   |Varchar(70)|Last Name of Customer|
|Address|Varchar(60)|Customer Full Address
|Contact_No|INT|Customer Contact Number

#### Table 2 Employee


| Column | Type     | Description                       |
| :-------- | :------- | :-------------------------------- | 
|Employee_id|INT | Employee ID Number
 |First_Name| varchar(80)|First Name of Employee
|Last_Name|varchar(70)|Last Name of Employee
|Address|varchar(80)|Employee Full Address
|Contact_No|int|Employee Contact Number
|Position|varchar(50)|Position of Employee
|Salary|varchar(60)|employee salary
|City|varchar(60)| employee city

#### Table 3 Cash_order

| Column | DataType     | Description                       |
| :-------- | :------- | :-------------------------------- | 
|Cashorder_id|Int|Cash Order ID Number
|Invoice_no|varchar(60)|Charge or Cash Invoice Number
|Brand_Name|Varchar(50)|Brand Name of Product
|Model|Varchar(50)|Model of Product
|Serial_No|INT|Serial Number of Product
|price|INT|Price of Product
|Unit_Type|Varchar(60)|Type of product unit sold

#### Table 4 Charge_order
| Column | DataType     | Description                       |
| :-------- | :------- | :-------------------------------- | 
|Chargeorder_id|INT|Charge Order ID Number
|Invoice_no|INT|Charge or Cash Invoice Number
|Brand_Name|Varchar(50)|Brand Name of Product
|Unit_Type|Varchar(50)|Type of product unit sold
|Model|Varchar(50)|Model of Product
|Serial_No|INT|Serial Number of Product
|Price|decimal(10,2)|Price of Product
|Down_Payment|Varchar(50)|Required Down Payment of Product

#### Table 5 Product
| Column | DataType     | Description                       |
| :-------- | :------- | :-------------------------------- | 
|Product_id|Int|Product ID Number
|Date_Recieved|DATE|Date Received of Product
|Brand_id|INT|Brand ID Number  of Product
|Model|VARCHAR(45)|Model of Product
|serial_no|INT|Serial Number of Product
|Availiblity|VARCHAR(45)|Serial Number of Product
|data_sold|VARCHAR(45)|Date of Product Sold
|Unit_Type|VARCHAR(45)|Type of product unit sold

#### Table 6 Supplier
| Column | DataType     | Description                       |
| :-------- | :------- | :-------------------------------- | 
|supplier_id|INT|Supplier ID number
|supplier_name|Varchar(50)|Name of Supplier
|supplier_address|Varchar(50)|Address of Supplier
|contact_no|INT|Contact Number of Supplier
|brand_id|INT|Brand Id Number of Product
## Screenshots


