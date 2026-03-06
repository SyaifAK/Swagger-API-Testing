# Swagger API Testing

## Description

This project contains API testing scenarios created using Swagger Petstore API.  
The goal of this project is to practice and demonstrate API testing skills using tools such as Postman and Swagger documentation.

The testing covers multiple endpoints including pet management, store orders, and user operations.

---

## Objectives

- Practice API testing using Swagger documentation
- Understand HTTP methods (GET, POST, PUT, DELETE)
- Validate API responses
- Test API endpoints using Postman
- Document API testing scenarios

---

## API Documentation

This project uses the public Swagger Petstore API:

https://petstore.swagger.io/

---

## Tools Used

- Postman
- Swagger UI
- Git
- GitHub

---

## API Endpoints Tested

### Pet

- Add new pet (POST /pet)
- Find pet by ID (GET /pet/{petId})
- Update pet (PUT /pet)
- Delete pet (DELETE /pet/{petId})

### Store

- Place an order (POST /store/order)
- Find order by ID (GET /store/order/{orderId})
- Delete order (DELETE /store/order/{orderId})

### User

- Create user (POST /user)
- Login user (GET /user/login)
- Logout user (GET /user/logout)
- Delete user (DELETE /user/{username})

---

## Test Scenarios

Examples of API test cases:

| Test Case ID | Endpoint     | Method | Expected Result          |
| ------------ | ------------ | ------ | ------------------------ |
| TC001        | /pet         | POST   | Pet successfully created |
| TC002        | /pet/{petId} | GET    | Return pet data          |
| TC003        | /pet/{petId} | DELETE | Pet successfully deleted |

---

## How to Run the Test

1. Open Swagger documentation:
   https://petstore.swagger.io/

2. Import API collection into Postman.

3. Execute API requests.

4. Verify:

- Status code
- Response body
- Response time

---

## Example Response Validation

Expected response example:

```json
{
  "id": 1,``
  "name": "doggie",
  "status": "available"
}
```
