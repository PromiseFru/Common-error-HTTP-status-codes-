### Common error HTTP status codes include:

* 400 Bad Request – This means that client-side input fails validation.
* 401 Unauthorized – This means the user isn’t not authorized to access a resource. It usually returns when the user isn’t authenticated.
* 403 Forbidden – This means the user is authenticated, but it’s not allowed to access a resource.
* 404 Not Found – This indicates that a resource is not found.
* 500 Internal server error – This is a generic server error. It probably shouldn’t be thrown explicitly.
* 502 Bad Gateway – This indicates an invalid response from an upstream server.
* 503 Service Unavailable – This indicates that something unexpected happened on server side (It can be anything like server overload, some parts of the system failed, etc.).
* 409 Conflict - This means there is conflict with the current state of the resource.

HTTP response status codes indicate whether a specific HTTP request has been successfully completed. Responses are grouped in five classes:

1. Informational responses (100–199)
2. Successful responses (200–299)
3. Redirects (300–399)
4. Client errors (400–499)
5. Server errors (500–599)
