# Eswar_Task1

**1. Environment Setup:**

Created a REST API using Spring Boot, MongoDB, and Lombok for streamlined development.

**2. API Operations:**

Utilized Postman to execute CRUD (Create, Read, Update, Delete) operations on the REST API.


**3. Supported CRUD Operations:**

Implemented the following CRUD operations within the REST API:
POST: Create new records.
GET: Retrieve existing records.
PUT: Update existing records.
DELETE: Remove records.

**4. Database Configuration:**

Established a MongoDB database named "CustomerDB" to store and manage data for the REST API.

**IMPLEMENTATION SCREENSHOTS AND RESULTS:**

**Project Files:**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/7fab142b-cc96-430b-a767-23fcff23623e)

**Created 2 packages** -->  dao, model
**Created java files:**  model --> Customer, CustomerController 
**Created interface:**  dao --> CustomerRepository

**Result:**
Port: 8080 (http)
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/8649effe-705e-43f6-9f3e-935609ee6638)

**Tool Postman (to perform CRUD Operations):**

**1.	POST** 
http://localhost:8080/api/addCustomer
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/2a992494-1d00-4ebf-ac29-2b07b54eccab)
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/5c37eddc-0146-4531-bdb8-eb04da3a087f)

**Database Result:**
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/e1afa98f-6249-4d1e-8ea9-78fc30b2b58f)

**If already exits:**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/a91636aa-ffa8-431a-90dc-e5ba9f2a2d61)

**2.GET**
http://localhost:8080/api/getCustomer
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/74215c29-238c-435d-8666-70d6c550299a)
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/bb62a93d-c309-43da-b9e5-8917619b55be)

**Database Result:** 
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/2fee2cbe-fba7-4ee5-8ce7-e03f485dd295)

**3.PUT**
http://localhost:8080/api/update/{id}
**•	If data exits in DB**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/62b7ed9b-6057-4e0f-9d7e-73d75e12649c)
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/6ac40ce7-c631-4599-9366-896d0dbe81dc)

**Database result:**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/0fd51df2-55fe-4407-b582-cfdfd82dd684)

**•	If data does not exist in DB**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/d4291f63-8e3a-4db2-8c1c-31226aa95eee)

**4.	DELETE**
http://localhost:8080/api/delete/{id}

**•	If data exist in DB:**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/48fca165-4b15-49ff-bd0b-c341b57510d2)

**After Deleting:** 
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/e5259c5c-ec99-43f2-963c-a595dbb30f8c)
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/d4aeff25-b83c-41cc-acb6-d64f89ec9014)

**Database result:**
 ![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/c84dfddb-fc9a-4d14-8b8c-ab1d3852da10)

**•	If data does not exist in DB:**
![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/a5e5051c-4f77-4655-992b-2c39da3c41f1)

 


