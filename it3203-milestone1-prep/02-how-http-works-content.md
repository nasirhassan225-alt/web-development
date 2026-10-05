# Topic Page 1 — How HTTP Works

## What HTTP does
HTTP provides a standard way for clients and servers to communicate. A browser does not simply "open" a website. It sends one or more HTTP requests for resources, and the server returns HTTP responses. A single webpage may require many separate requests for HTML, CSS, JavaScript, images, fonts, videos, and data.

## The basic request-response process
1. A user enters a URL or selects a link.
2. The browser identifies the destination server and requested resource.
3. The browser establishes the necessary network connection.
4. The browser sends an HTTP request.
5. The server processes the request.
6. The server sends an HTTP response.
7. The browser uses the returned content to display or update the page.
8. Additional resources can trigger more HTTP requests.

## HTTP request
An HTTP request tells the server what the client wants. It can contain a method, a resource path, headers, and sometimes a body.

Example concepts to explain:
- GET requests a resource.
- POST commonly sends new data.
- PUT or PATCH can update data.
- DELETE requests removal of a resource.

## HTTP response
A response tells the client the result of the request. It normally includes a status code, response headers, and possibly a message body.

Common status-code examples:
- 200 OK — the request succeeded.
- 301 Moved Permanently — the resource has moved.
- 404 Not Found — the requested resource could not be found.
- 500 Internal Server Error — the server encountered an unexpected problem.

## Headers
Headers carry metadata. They can describe content type, accepted formats, caching behavior, cookies, authentication information, and security rules.

## Message body
The message body is where actual content can be carried. Depending on the request or response, it may contain HTML, JSON, form data, images, or another file type.

## Required table idea
| Step | What happens |
| --- | --- |
| 1 | User enters a URL |
| 2 | Browser connects to the destination |
| 3 | Browser sends an HTTP request |
| 4 | Server processes the request |
| 5 | Server sends an HTTP response |
| 6 | Browser renders or uses the returned content |

## Suggested image
A labeled request/response diagram is ideal for this page.
