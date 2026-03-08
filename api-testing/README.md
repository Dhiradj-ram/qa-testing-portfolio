# API Testing (Postman)

This folder contains API testing examples created using Postman.

The collections demonstrate how REST APIs can be tested using different scenarios such as workflow testing, response validation and invalid input handling.

---

## Grocery Store API

This collection tests a sample grocery store REST API.

The tests simulate a realistic e-commerce workflow including:

* checking API status
* retrieving available products
* creating a cart
* adding items to the cart
* updating item quantities
* replacing and deleting cart items
* creating an order
* retrieving, updating and deleting orders

---

## Response Validation

The tests include response validation such as:

* verifying HTTP status codes
* validating response body structure
* checking returned data types and values
* ensuring expected fields are present in the response

---

## Negative Testing

The collection also contains negative test scenarios to verify how the API handles invalid input, such as:

* invalid product category
* invalid result limits
* boundary value testing for query parameters

---

## Tools Used

* Postman
* REST APIs
* JSON response validation

* ## Additional API Collections

### Tool Rental API

This collection tests a simple tool rental system API.

The workflow includes:

* retrieving available tools
* registering an API client
* creating a rental order
* retrieving orders
* updating orders
* deleting orders
* verifying that deleted orders cannot be retrieved

---

### Trello API

This collection demonstrates testing of the Trello REST API.

The workflow includes:

* retrieving boards
* creating a new board
* creating lists
* creating cards
* moving cards between lists
* deleting a board
* verifying that deleted resources are no longer accessible


---

## Tools Used

* Postman
* REST APIs
* JSON responses
