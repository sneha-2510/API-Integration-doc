# What is an API?

An API, or Application Programming Interface, is a set of rules and protocols that allows different software applications to communicate with each other. APIs define the methods and data formats that developers can use to interact with a service or platform. They provide a way for developers to access specific features or data without needing to understand the underlying code or infrastructure.

# 6 Step Guide for API handling 

## Step 1: http methods
Generally, the five primary HTTP methods are used as follows:

| Method | Description |
|----------|----------|
| GET   | Read a specific resource (by an identifier) or a collection of resources.    | 
| PUT    | Replace a specific resource (by an identifier) or a collection of resources. Can also be used to create a specific resource if the resource identifier is known before-hand.     | 
| PATCH    | Update a specific resource (by an identifier) or a collection of resources. This can be thought of in some ways as a ‘partial update’ vs the replace that PUT performs.     | 
| DELETE   | Remove/delete a specific resource by an identifier.     | 
| POST   | Create a new resource. Also a catch-all verb for operations that don’t fit into the other categories.     | 

## Step 2: Status code & request header

| Status Code | Description |
|----------|----------|
| 1xx | Informational |
| 2xx | Success |
| 3xx | Redirection |
| 4xx | Client Error |
| 4xx | Server Error |

```
- Request Headers: 
- Request ip: 
- Request user agent: 
- Request path variables 
- Query parameter
```
## Step 3: Response handling

- JSON 
- XML 
- response header
- response caching
- response cookie
- redirect handling
- handle image

## Step 4: Authentication

- OAuth
- JWT
- Bearer Token
- API keys
- Cookies
- session
- token 
- referesh token

## Step 5: API Rate Limiting
## Step 6: Advance topics
- REST 
- GraphQL
- SOAP
- Webhooks
- Websockets
