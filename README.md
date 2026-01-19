# Swagger Petstore API Tests (Postman)

## 📌 Project description
This project contains API tests for the public Swagger Petstore API.
The tests were created using Postman and cover both positive and negative scenarios.

## 🔧 Tools
- Postman
- Swagger Petstore (OpenAPI)

## 📂 API Endpoints covered
- POST /user — Create user
- GET /user/{username} — Get user
- PUT /user/{username} — Update user
- GET /user/login — Login user

## 🧪 Test scenarios
### Positive
- Create user with valid data
- Get existing user
- Login with valid credentials
- Create user with empty username
- Update user
    
### Negative
- Login with wrong password
- Create user with empty required fields

## ▶️ How to run tests
1. Import the Postman collection from the `postman/` folder
2. Use Postman Collection Runner
3. Review status codes and test results

## 👨‍💻 Author
Serhii
