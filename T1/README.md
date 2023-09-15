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

# IMPLEMENTATION SCREENSHOTS AND RESULTS:

**Project Files:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/c333f89f-7cf0-498e-be1e-8095b643783d)
 
**Created 2 packages** -->  dao, model
**Created java files:**  model --> Customer, CustomerController 
**Created interface:**  dao --> CustomerRepository

**Result:**
Port: 8080 (http)


![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/37e63f57-1b5c-49fa-becf-317edd13e574)

**Tool Postman (to perform CRUD Operations):**

**1.	POST** 
http://localhost:8080/api/addCustomer

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/ca00dc1c-4d43-4c4e-95d1-03ba2a0cd599)

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/0f2e6ba6-9588-4b10-b0ea-2ca4533bab80)

**Database Result:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/1be7c8b3-b31f-4345-9fde-1cbcda61e377)

**If already exits:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/20441685-f08c-4372-a81e-ddb9faa226ac)

**2.GET**
http://localhost:8080/api/getCustomer

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/01acee24-ae81-4145-b521-d9d4ba6ad302)


![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/37805c7b-aea9-48eb-952d-1d9d53811cbd)

**Database Result:** 

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/97d7d916-a144-43b6-a7f0-7df5e2547c7f)

**3.PUT**
http://localhost:8080/api/update/{id}
**•	If data exits in DB**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/f2796a7c-038b-428d-8a74-ffddb0f7e88d)

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/6088b801-6c09-40a3-880d-a12c1303ddf1)

**Database result:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/46899ca0-a8f5-4d33-b82f-64d7486330aa)

**•	If data does not exist in DB**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/2cd82c42-9817-4fbb-853d-5b7ffe765292)

**4.	DELETE**

**•	If data exist in DB:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/bc6cfb15-7e8c-4c16-af3f-83252e45d62e)

**After Deleting:** 

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/6c86f5b6-9124-484b-afca-195b945e19a0)

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/fd4f1d03-7874-4e01-851e-8ad890d41ad6)

**Database result:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/2336c603-04a7-42da-b9d5-97d86e82f5bc)

**•	If data does not exist in DB:**

![image](https://github.com/eswarganesan/Eswar_Task/assets/104221146/fb230efa-a157-4e63-8d88-305895068b48)

 


