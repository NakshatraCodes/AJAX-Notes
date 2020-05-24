# Notes for HTTP, AJAX and further

## Hyper Text Transfer Protocol
Communicates between server and client
HTTP Requests and Responses

It is completely stateless - meaning (Every request is completely independent. It doesn't remember anything about the previous request.)

HTTPS is Hyper Text Transfer Protocol Secure
Data is encrypted using SSL and TLS
 - GET - Retrieves data from the server
 - POST - Submit data to the server
 - PUT - Update data which already exists on the server
 - DELETE - Delete data from the server

HTTP status codes

- 1XX: Informational - Request recieved / processing
- 2XX: Success - Successfully recieved / understood / accepted
- 3XX: Redirect - Further action must be taken / redirect
- 4XX: Client Error - Request does not have what it wants
- 5XX: Server Error - Server failed to fulfil apparent valid request

### Common status codes

 - 200 OK
 - OK created
 - 301 Moved to new URL
 - 304 Not Modified (Cached Version)
 - 400 Bad Request
 - 401 Unauthorised
 - 404 Not found
 - 500 Internal Server Error

- HTTP/1.1 Baseline and HTTP/2 Multiplexing



## AJAX and XHR

- Asynchronous JS and XML
- Set of technologies
- Send and recieve data asynchronously
- Does not interfere with current web page
- JSON has replaced XML

- **Allows us to make requests without loading the entire webpage.**
- **Enables users to change or make small requests in the backkground without disturbing the webpage.**

## XMLHttpRequest (XHR Object)

- API in the form of an object
- Can be used with other data like JSON/plain text
- Can be used with other protocols
- Provided by browser's JS environment

### Libraries 

- jQuery
- Axios
- Fetch API
- Node HTTP Module
- Superagent
- Prototype

