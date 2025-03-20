# MockServer

A simple mock server built using [my-json-server](https://my-json-server.typicode.com/) to provide a set of product data for testing and development purposes.

## API Endpoint  
You can access the mock server and its resources using the following link:  

🔗 **[Mock Server URL](https://my-json-server.typicode.com/rizosamuel/MockServer)**  

## Available Routes  

📌 Get all Products

Request:
GET https://my-json-server.typicode.com/rizosamuel/MockServer/Products

Response:
Returns a list of all products in JSON format.

📌 Get a Product by ID

Request:
GET https://my-json-server.typicode.com/rizosamuel/MockServer/Products/{id}

Response:
Returns the product details for the given {id}.

📌 Create a New Product (Mocked)

    Note: Since this is a mock server, data persistence is not supported. The request will return a successful response but won’t actually create new records.
    
Request:
POST https://my-json-server.typicode.com/rizosamuel/MockServer/Products

Response:
Returns the newly created product (mocked response).

📌 Update a Product (Mocked)

    Note: Since this is a mock server, data updates are not persisted.

Request:
PUT https://my-json-server.typicode.com/rizosamuel/MockServer/Products/{id}

Response:
Returns the updated product details (mocked response).

📌 Delete a Product (Mocked)

    Note: The deletion is only simulated; the data will not actually be removed.

Request:
DELETE https://my-json-server.typicode.com/rizosamuel/MockServer/Products/{id}

Response:
Returns a success message indicating the product was "deleted" (mocked).

## Usage  
This mock API is useful for front-end development, prototyping, and testing without requiring a real backend.

---

Feel free to modify the mock data as needed. 🚀
