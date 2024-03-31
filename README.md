# SalesDataAnalysis

### Creating the Sales 2019 table
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/741d0193-82b3-427c-bac4-d6b9a268c0ed)

### Importing the csv files
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/48b64342-3fae-4d51-8a4f-2c192e858638)

#### Sales_2019_table
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/dc0d1f43-1544-4154-b0d6-17b0e872c149)

### Deleting rows
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/dd353f9e-4061-4599-8d0b-a4d2dea4d763)

### Result: 186,850 to 186,495 rows
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/4b4a0c49-465d-45f2-befe-8c39ae21f9b7)

### Changing the data types
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/19ccac95-13d1-494d-84ec-c5308dd4e45b)

### Result:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/59f1abb5-15b6-4c3a-b7b7-3ca3bb18d5ed)

### Stored Procedure for Data Versioning
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/f727b92b-46a2-4729-890c-a9590a46eda5)

### Result:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/cf0ca688-2b3e-4ce1-8f3f-e8f4f07ddd0f)

## TRANSFORMATION MODULE
### Data Versioning of sales_2019_nonull:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/3a5c2bb8-4728-4b4b-b9d1-223882ac039e)

### Checking of null values:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/2452c96a-ad42-4bb6-a3a9-c6af607077f2)

### Stored Procedure for removing of null values
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/2a7f1cea-bad3-4fc0-90e5-c328ecbabca4)

### sales_2019_nonull
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/a7005ca0-629f-45ea-b99e-cb6eba29ca32)

### Stored Procedure for creating table:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/59863ccf-9590-439c-a945-1854a6542806)

### Stored Procedure for removing duplicate values
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/5fd9ad32-04fc-4ea6-898c-1f1c58a91465)

### sales_2019_noduplicates
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/9c15a9f7-c96c-4af6-9737-d4c0bce49bb3)

### Data Versioning of sales_2019_standardization:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/ce1930fd-b1ab-41fe-bc33-dcfdba2cc30e)

### Standardization process:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/5a588bb5-f8c3-4c4a-a69b-346928c5d2ec)

### Data versioning of sales_2019_parsing
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/41547cdc-7d9e-4773-a294-436885def85d)

### Parsing of order_date one by one
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/57bc5ff0-8bfe-4a03-8281-7c135f177744)

### Updating date and time column
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/45bc91e0-6f1f-489e-aa55-47b04c127b28)

### Stored Procedure in making concept hierarchy for order_date column
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/f889a60d-1958-480f-8114-ab7565dc9878)

### sales_2019_parsing as of now:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/3934566d-a043-4e08-a921-f1e324d8edf1)

### Stored Procedure for updating  the order_date_year, order_date_quarter, order_date_month, order_date_week, order_date_day
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/eaffc4b7-3fb5-4df8-86f1-8517dd85d103)

### Parsing of purchase_address
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/408e7dd4-0bcf-4c3f-a04e-970e93c8815c)

### Updating of street, city, state, and zipcode column
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/93455503-6a18-4ba3-a022-f4b0b2cf25c5)

### Data versioning of sales_2019_transformed:
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/ea161f86-f404-41f2-9874-e5d8923ef519)

## LOADING MODULE
### Creating of Order Dimension
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/96f08553-c0a8-46a3-a574-fac05e05f2a9)

### order_dimension table
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/ca49b08f-2f03-489e-bdbc-e4f14e8e915f)

### Creating of Product Dimension
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/262ce3a7-336c-43f7-903a-f4df1dbdca50)

### Creating of Order Date Dimension
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/87d90b45-3553-4628-93bf-e6e3326429a5)

### Creating of Address Dimension
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/8c130544-2139-491d-a7f6-611905d69f0d)

### Creating of Sales Fact Table 
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/08ad944f-f4c2-4fae-8873-68883561e260)

### Sales Fact Table
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/b75d9085-1140-405f-af85-0f54e6d151de)

### Adding Foreign Keys to Sales Fact Table
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/964ba565-363e-4c4c-b264-87f97ce89546)

## INSIGHTS
![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/90f3e1c6-8dcf-40fc-96af-c14631583de6)
- Macbook Pro Laptop have the highest total sales in each month in 2019 with a total of 8,032,500.

![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/2a726909-c197-410a-896d-c616882da737)
- A total of 34,465,537.94 for the whole year.

![image](https://github.com/ochengco-paolo/SalesDataAnalysis/assets/140794262/d75d4ae2-df9e-4ff3-ad4e-d17acd5b70d6)
- Macbook Pro Laptop have the highest total sales in each month in 2019 with a total of 8,032,500.


