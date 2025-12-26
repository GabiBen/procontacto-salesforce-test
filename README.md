# Salesforce Technical Test – PMO

## Overview
This repository contains the resolution of the technical assessment for ProContacto.
The objective of this test is to demonstrate conceptual understanding of Salesforce,
basic HTTP knowledge, and the ability to document technical processes clearly,
with a PMO-oriented approach.

## Exercises
The following sections describe each exercise and its resolution.

---

## Exercise 1 – Environment Setup
Visual Studio Code and Git were installed successfully in order to work with the repository and documentation.

---

## Exercise 2 – HTTP Concepts

### 1. What is an HTTP server?
An HTTP server is a system that receives requests from clients (such as browsers or applications) and responds using the HTTP protocol by returning the requested resources or data.

### 2. What are HTTP verbs? Mention the most common ones
HTTP verbs define the action to be performed on a resource.
The most common ones are:
- GET: retrieve information
- POST: send or create information
- PUT: update information
- DELETE: remove information

### 3. What is a request and a response? What are headers?
A request is the message sent by the client to the server.
A response is the message sent back by the server after processing the request.

Headers contain metadata about the communication, such as content type or authentication details.

### 4. What is a query string?
A query string is additional information sent in the URL as key–value pairs after the `?` symbol.

Example:
`/users?id=10&status=active`

### 5. What is a response code?
A response code is a numeric value that indicates the result of an HTTP request.

Examples:
- 200: successful request
- 404: resource not found
- 500: internal server error

### 6. How is data sent in a GET request and in a POST request?
In a GET request, data is sent through the URL as a query string.
In a POST request, data is sent in the body of the request.

### 7. Which HTTP verb does a browser use when accessing a web page?
Browsers generally use the GET verb to request web pages.

### 8. What are JSON and XML?
JSON and XML are data exchange formats.

JSON example:
json
{
  "name": "Juan",
  "email": "juan@mail.com"
}

XML example:
<user>
  <name>Juan</name>
  <email>juan@mail.com</email>
</user>


### 9. What is SOAP?
SOAP is a communication standard based on XML, commonly used in traditional enterprise systems and characterized by a strict structure.

### 10. What is REST?
REST is an architectural style for web services that uses HTTP, standard HTTP verbs and commonly JSON to exchange data in a simple and flexible way.

### 11. What are headers in a request? What is the Content-Type header used for?
Headers provide additional information about the request.
The Content-Type header specifies the format of the data being sent, such as application/json.


## Exercise 3 – Postman Requests
Three HTTP requests were executed using Postman in order to interact with the provided endpoint.

### GET request
A GET request was sent to retrieve the existing contacts stored in the service.

- Method: GET  
- URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json  

The response returned a JSON object containing the list of stored contacts.

(Screenshot: GET request response)

### POST request
A POST request was sent to create a new contact.

- Method: POST  
- URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json  

Request body:
{
  "name": "Gabriel Benitez",
  "email": "gabriel.benitez@procontacto.com.mx"
}
The response returned a unique identifier for the newly created record.

(Screenshot: POST request response)

GET request (verification)
A final GET request was executed to verify that the new contact was successfully stored.

The response confirmed that the newly created record appears in the list of contacts.

(Screenshot: GET verification response)

---

## Exercise 4 – Trailhead Modules
(ACÁ DESPUÉS PEGÁS EL LINK A TU PERFIL DE TRAILHEAD)

---

## Exercise 5 – Salesforce Objects and Relationships
(ACÁ DESPUÉS PEGÁS EL CONTENIDO TEÓRICO QUE YA ARMAMOS)

---

## Exercise 6 – Salesforce Concepts
(ACÁ DESPUÉS VAN LAS DEFINICIONES)

---

## Exercise 7 – Apex Trigger (Conceptual Approach)
(This exercise is explained from a conceptual point of view, aligned with a PMO role.)
