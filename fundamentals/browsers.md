# Browsers - Summary

A **web browser** is an application that allows users to access and interact with websites on the Internet. Examples of popular browsers include **Google Chrome**, **Mozilla Firefox**, **Microsoft Edge**, and **Safari**.

Browsers act as a bridge between the user and the web. They request resources from web servers and display them in a human-readable format.

## What a Browser Does

When you type a URL like `https://example.com` into the browser, it performs several steps:

1. **URL Interpretation**
   - The browser reads the URL and identifies the protocol (`http` or `https`) and the domain name.

2. **DNS Lookup**
   - The browser uses DNS to translate the domain name into an IP address.

3. **Establishing a Connection**
   - The browser connects to the server using TCP.
   - If the website uses HTTPS, the browser performs a TLS/SSL handshake to create a secure encrypted connection.

4. **Sending an HTTP Request**
   - The browser sends an HTTP request (like `GET`) asking the server for the webpage content.

5. **Receiving the HTTP Response**
   - The server sends back an HTTP response containing headers and the requested content (HTML, CSS, JavaScript, images, etc.).

6. **Rendering the Page**
   - The browser reads the HTML and builds the page structure (DOM).
   - It loads and applies CSS styles.
   - It runs JavaScript code.
   - Finally, it displays the website on the screen.

## Rendering Engine

The **rendering engine** is responsible for converting HTML and CSS into a visible webpage. Different browsers use different engines, such as:

- **Blink** (Chrome, Edge)
- **Gecko** (Firefox)
- **WebKit** (Safari)

## Browser Cache

Browsers store files like images, scripts, and stylesheets in a **cache** to speed up future visits. This reduces loading time and saves bandwidth.

## Cookies and Storage

Browsers can store small pieces of data to remember user information:

- **Cookies**: used for sessions, login status, preferences, and tracking.
- **Local Storage / Session Storage**: used for storing larger amounts of data on the client side.

## Key Takeaways

- A browser requests web resources and displays them as webpages.
- It uses DNS, TCP, HTTP/HTTPS to communicate with servers.
- It renders websites by processing HTML, CSS, and JavaScript.
- Caching and storage improve performance and user experience.