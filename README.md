# Eswar_Task

**T1**

**1. Environment Setup:**

Created a REST API using Spring Boot, MongoDB, and Lombok for streamlined development.

**2. API Operations:**

Utilized Postman to execute CRUD (Create, Read, Update, Delete) operations on the REST API.

**3. Supported CRUD Operations:**

Implemented the following CRUD operations within the REST API: POST: Create new records. GET: Retrieve existing records. PUT: Update existing records. DELETE: Remove records.

**4. Database Configuration:**

Established a MongoDB database named "CustomerDB" to store and manage data for the REST API.

==========================================================================================================================================

**T2**

**Here are the steps to implement the Server Management API using Swagger Editor, Spring Boot, and Postman:**

**1. Design the API in Swagger Editor**
I would open the OpenAPI spec in the Swagger Editor at https://editor.swagger.io/
Modify and tweak the YAML to get the API definition finalized
The editor validates the spec and provides real-time feedback

**2. Generate the Spring Boot code**
Once defined, use the Swagger Codegen to generate a Spring Boot server stub
Can generate from the editor using the UI, or download and run Codegen
This will produce a Spring Boot project with auto-generated code for the API

**3. Implement the server logic**
Add business logic to the API controller methods generated in the code
Write service classes that the controller calls to do real work
Implement models and repository interfaces as needed
Get a basic working Spring Boot app serving the API endpoints

**4. Document using Swagger UI**
The Spring Boot app will embed Swagger UI using the OpenAPI spec
This makes the API documentation interactive and discoverable

**5. Use Postman for testing**
Import the OpenAPI spec into Postman
Will create collections for the endpoints
Can use Postman to send requests and test API responses
Covers validation, success/error flows
This gives a nice workflow for going from API design to implementation using standard tools like Swagger, Spring Boot, and Postman. The focus is on the contract-first approach with OpenAPI spec at the center.
