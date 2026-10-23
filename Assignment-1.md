Assignment-1.md
# Assignment 1 – What Happens Between Typing a URL and Seeing the Page?

## Introduction

When we type a URL into a web browser and press Enter, several steps happen before the website appears on our screen.

## Steps Involved

1. *URL Entry:* The user enters a website address, such as https://example.com, into the browser.

2. *Cache Check:* The browser checks whether it can reuse previously stored resources or connection information.

3. *DNS Lookup:* The browser finds the IP address associated with the domain name.

4. *Connection Establishment:* The browser establishes a connection with the server. For HTTPS, TLS helps secure the communication.

5. *HTTP Request:* The browser sends an HTTP request, such as GET /index.html, to request a resource.

6. *Server Response:* The server processes the request and sends a response containing a status code, such as 200 OK, and the requested content.

7. *HTML Parsing:* The browser reads the HTML and builds the Document Object Model (DOM).

8. *Loading Resources:* The browser discovers and requests additional resources, including CSS, JavaScript, images, and fonts.

9. *Rendering:* The browser processes CSS, calculates the layout, and paints the page on the screen.

10. *JavaScript Execution:* JavaScript can make the page interactive and update its content.

## Conclusion

A web page appears through several steps involving the browser, DNS, network connections, HTTP requests, the server, and the browser's rendering process. These steps work together to display a website to the user.
