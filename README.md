API Testing Project – JSONPlaceholder

Project Overview: This project demonstrates API testing performed on the JSONPlaceholder fake REST API using Postman.
The goal of this project is to validate API functionality, response structure, and performance through structured test cases and automated test scripts. 

API Tested: JSONPlaceholder: https://jsonplaceholder.typicode.com/

Tools & Technologies:
Postman
JavaScript (for Postman test scripts)

Test Coverage: 
The following HTTP methods were tested:
GET – Retrieve data from API
POST – Create new resources
PUT – Update existing data
DELETE – Remove resources

Testing Approach: 
Functional Testing: 
Verified all endpoints are working correctly
Validated request and response flow
Positive Testing:
Tested API with valid inputs
Verified expected responses and correct data returned
Negative Testing:
Tested API with invalid or missing inputs
Verified proper error handling and status codes

Validations Performed:
Status Code Validation (200, 201, 404, etc.)
Response Body Validation
JSON Structure Validation
Response Time Validation
Data Integrity Checks

Sample Test Scenarios:
Verify GET request returns list of posts
Validate POST request creates new resource
Check PUT request updates existing data correctly
Ensure DELETE request removes resource successfully
Validate error response for invalid endpoints

Results:
All test cases were executed successfully, and API responses were validated against expected outcomes.
This project helped in understanding real-world API testing practices and automation using Postman scripts.
