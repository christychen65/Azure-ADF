# Azure-ADF-Instruction-Manual
This instruction manual aims to demonstrate a sample of work using Azure ADF with Snowflake.
 <br />
### Table of contents
* [1. Subscription](#1)
* [2. Resource Group](#2)
* [3. Storage Account](#3)
* [4. SQL Servers](#4)
* [5. Create SQL Database](#5)
* [6. Azure Data Factory](#6)
* [7. Azure Data Studio](#7)

<a id="1"></a>
### 1. Subscription
 <br />

<a id="2"></a>
### 2. Resource Group
* Create a resource group, enter a resource group name, and change the region to Canada Central

<img width="936" alt="Screenshot 2023-05-23 at 08 35 30" src="https://github.com/christychen65/Azure-ADF/assets/132826012/54d9bfe3-292d-4e1c-9e71-7f135c26d2e3">

<img width="936" alt="Screenshot 2023-05-23 at 10 05 05" src="https://github.com/christychen65/Azure-ADF/assets/132826012/ae97e01d-759e-45af-9e46-e8837f31ffae">


<a id="3"></a>
### 3. Storage Account
* Create a storage account, enter a storage account name, and change redundancy to Locally-redundant storage (LRS)
<img width="936" alt="Screenshot 2023-05-23 at 10 10 23" src="https://github.com/christychen65/Azure-ADF/assets/132826012/6a3faa06-1560-46a8-afe2-0ee16b2b4fb7">
<img width="936" alt="Screenshot 2023-05-23 at 10 14 48" src="https://github.com/christychen65/Azure-ADF/assets/132826012/fa19405c-964d-42b1-9a38-b4ced2a0a616">

<a id="4"></a>
### 4. SQL Servers
* Create an SQL database server, find SQL servers in Azure Services. If it does not appear on the web, search for it using the search bar. 
<img width="936" alt="Screenshot 2023-05-23 at 10 24 48" src="https://github.com/christychen65/Azure-ADF/assets/132826012/d332d114-4ff1-437c-9143-ef40c32f18bb"> <br />
* Enter a name, change the location to Canada Central, choose to use SQL authentication, then enter the server admin login and password. Review and create.  <br />

<img width="936" alt="Screenshot 2023-05-23 at 14 27 40" src="https://github.com/christychen65/Azure-ADF/assets/132826012/f77226f1-b5eb-49cc-8b99-9c8cf6719e32">

<a id="5"></a>
### 5. Create SQL Database
* Enter the resource group and database name, and select the server that was created in step 4. For the backup storage redundancy, choose locally-redundant backup storage. Review and connect. <br />
<img width="936" alt="Screenshot 2023-05-23 at 14 35 05" src="https://github.com/christychen65/Azure-ADF/assets/132826012/40bc4452-2e3c-4115-aea1-e249ebb1a2c9">
<img width="936" alt="Screenshot 2023-05-23 at 14 39 11" src="https://github.com/christychen65/Azure-ADF/assets/132826012/092a630b-635b-4b72-ace9-bf8fb725ef05">

<a id="6"></a>
### 6. Azure Data Factory
* Create an Azure Data Factory, select the resource group that was created in step 2, enter a name, and change the region.
<img width="936" alt="Screenshot 2023-05-23 at 14 42 51" src="https://github.com/christychen65/Azure-ADF/assets/132826012/66fc7dd5-2b10-49f2-bcac-7128637206d4">
<img width="936" alt="Screenshot 2023-05-23 at 14 45 33" src="https://github.com/christychen65/Azure-ADF/assets/132826012/8877e324-291e-4796-a74b-ad43beebe61d">

<a id="7"></a>
### 7. Azure Data Studio
* In Azure Data Studio, click on 'New Connection'.
* Go back to Microsoft Azure, find the SQL database (db) that was just created, copy the server name, and paste it into Azure Data Studio.
<img width="936" alt="Screenshot 2023-05-23 at 14 53 52" src="https://github.com/christychen65/Azure-ADF/assets/132826012/765fd067-928b-4dba-9552-1bb9cb319dc4"> <br />
*  Enter the username (test) and the password in the connection details, then connect. If an error occurs, go back to Microsoft Azure and check the server firewall settings.   <br />

<img width="936" alt="Screenshot 2023-05-23 at 14 57 00" src="https://github.com/christychen65/Azure-ADF/assets/132826012/c97dc542-ab78-4907-b463-cfdc44618917">
<img width="936" alt="Screenshot 2023-05-23 at 14 58 17" src="https://github.com/christychen65/Azure-ADF/assets/132826012/29248140-5b82-4a0d-8a04-6fb878028cfa">

* Choose the selected network and add your client IPv4 address.
<img width="936" alt="Screenshot 2023-05-23 at 15 01 14" src="https://github.com/christychen65/Azure-ADF/assets/132826012/d1f9f4b7-364b-4b9e-adaa-6720308033b3">
<img width="936" alt="Screenshot 2023-05-23 at 15 01 21" src="https://github.com/christychen65/Azure-ADF/assets/132826012/b853d8c9-3771-47e2-8cc7-0c03d5947d8b">



