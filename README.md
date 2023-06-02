# how-web-works

## What is HTTP?

Stands for Hyper Text Transfer Protocol, is a protocol for fetching data from a server or send data to a server.

## What is a URL?

Stands for Uniform Resource Locator, is the address of a given unique resource on the Web

## What is DNS?

Stands for Domain Name System,  is the translation of human-friendly domain namesto a numeric IP address; this process of mapping a domain name to the appropriate IP address is known as a DNS lookup (Like a Dicionary of IP address) '

## What is a query string?

Are a way to structure additional information for a given URL. Parameters are added to the end of a URL after a ‘?’ symbol, and multiple parameters can be included when separated by the ‘&’ symbol. 

## List two HTTP Verbs and their use cases.

- GET - get some data from the server (most pages, search forms)
- POST - send some data to the server (pages that change data on server)
- PUT - method replaces all current representations of the target resource with the request payload (Update existend data on server)
- DELETE - method deletes the specified resource. (Delete specified data on the server)


## What is an HTTP request?

An HTTP request is a request from a client to a server which follows the HTTP protocol, The aim of the request is to access a resource on the server.
    
## What is an HTTP response?

An HTTP response is a response from a server to a client which follows the HTTP protocol, he aim of the response is to provide the client with the resource it requested, or inform the client that the action it requested has been carried out.
    
## What is an HTTP header? Give a couple examples of request and response headers you have seen.

   - Headers provide additional information about the request or the response. Here are some examples:
   - Request headers: Host, User-Agent, Accept, Cookie, Cache-Control
   - Response headers: Content-Type, Last-Modified, Set-Cookie, Cache-Control\
    
## What happens when you type a URL in a browser?

1. Your browser “resolves” the URL name into an IP address using DNS  (Domain Name System)  lockup .
2. The browser initiates a TCP connection with the server.
3. The browser sends an HTTP request to the webserver. including headers (info about browser, any previous cookies, and other things)
4. The server handles the request and sends back a response.  with a status code (200 if it was sucessful)
5. The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, JavaScript, etc)
6. The browser makes separate HTTP requests for those resources and receives response from the server for each
