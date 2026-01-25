# Postman API Testing Project – JSONPlaceholder

This repository contains a Postman collection created to test the **JSONPlaceholder** public REST API.
The project demonstrates basic and advanced API testing concepts, including positive and negative scenarios, response validation, and performance checks.

## 📌 API Used

* **JSONPlaceholder** – Fake Online REST API for Testing and Prototyping
* Base URL: [https://jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com)

## 📁 Project Contents

* Postman Collection (v2.1)
* Automated test scripts written in JavaScript using Postman (`pm.test`)

## 🔍 Covered Endpoints & Scenarios

### GET Requests

* **GET /posts**

  * Verify status code (200)
  * Validate response structure (array)
  * Performance test (response time)

* **GET /posts/{id}** (positive case)

  * Validate correct post data
  * Status code and response content checks

* **GET /posts/{id}** (negative case)

  * Non-existing post
  * Status code and empty response validation

### POST Requests

* **POST /posts** (positive case)

  * Create a new post
  * Validate response body fields
  * Status code check (201)

* **POST /posts** (negative case)

  * Empty request body
  * Demonstrates API behavior for invalid input

### PUT Requests

* **PUT /posts/{id}** (positive case)

  * Update existing post
  * Validate updated fields
  * Performance test

* **PUT /posts/{id}** (negative case)

  * Update non-existing post
  * Error handling and response validation

## 🧪 Test Types Implemented

* Status code validation
* Response body validation
* Negative testing
* Performance testing (response time)

## 🚀 How to Run the Tests

1. Download and install **Postman**
2. Import the collection JSON file into Postman
3. Run requests individually or use **Collection Runner**

## 🛠 Tools & Technologies

* Postman
* REST APIs
* JavaScript (Postman Test Scripts)
* JSON

## 📌 Notes

* JSONPlaceholder is a mock API; some negative test cases intentionally fail due to API limitations.
* No authentication or environment variables are required for this project.

## 📄 License

This project is for learning and demonstration purposes only.
