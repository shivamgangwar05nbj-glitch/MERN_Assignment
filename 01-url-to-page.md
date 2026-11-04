# Assignment 1 – What Happens Between Typing a URL and Seeing the Page?

Introduction:-

When we type a URL (Uniform Resource Locator) into a web browser and press Enter, several processes happen in the background to load the website. The browser communicates with different servers and retrieves the required files to display the webpage.

Step-by-Step Process:-

1\. Entering the URL: First, we type a website address, such as `www.google.com`, into the browser and press Enter.

2\. Browser Cache: The browser checks its cache to see whether the website's required resources are already stored.

3\. DNS Lookup: DNS (Domain Name System) converts the domain name into an IP address so that the browser can locate the web server.

4\. Establishing Connection: The browser establishes a connection with the server using TCP (Transmission Control Protocol).

5\. TLS Handshake: If the website uses HTTPS, a TLS handshake takes place to create a secure and encrypted connection.

6\. Sending HTTP Request: The browser sends an HTTP request, such as a GET request, to the web server to ask for the webpage.

7\. Server Processing: The server receives the request, processes it, and collects the required resources, such as HTML, CSS, JavaScript, and images.

8\. HTTP Response: The server sends an HTTP response containing the requested data and a status code, such as 200 OK.

9\. Rendering the Webpage: Finally, the browser reads the HTML, applies CSS styles, executes JavaScript, and displays the webpage on the screen.

Conclusion:-

When we type a URL and press Enter, the browser performs several steps to communicate with the web server. These steps help retrieve website data and display the webpage properly. This entire process happens within a few seconds.

Flow: URL → DNS → TCP → TLS → HTTP Request → Server Response → Browser Rendering → Webpage.