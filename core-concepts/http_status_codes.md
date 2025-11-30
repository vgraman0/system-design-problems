# HTTP Status Codes

## 1xx: Informational Response

- 100 Continue:

## 2xx: Success

- 200 OK: standard response for successful HTTP requests


## 3xx: Redirection

- 300 Multiple Choices: multiple options for the resource that the client may choose

- 301 Moved Permanently: the link target was moved such that the request and future similar requests should be directed to the given URI.
    - Browsers will cache this request, meaning subsequent requests might go directly to the long URL, bypassing the server

- 302 Temporary Redirect: the resource is available via an alternate URL.
    - Browsers do not cache this response, ensuring future requests will go through the server.

## 4xx: Client Error

## 5xx: Server Error

