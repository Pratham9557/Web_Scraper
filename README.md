# Web_Scraper
Here is a simple Web Scraping example to understand the concept of Web Scraping

#Key Points:
Install the required libraries using pip (Here we are using the BeautifulSoup class from the bs4 module and 'requests' to send requests to the URL)
Make sure the pip is up to date
Be sure to write the module/class names correctly (case-sensitive)

#Status Code
In web scraping, checking the HTTP status code is a common practice to determine whether the HTTP request to a website was successful or encountered an error. HTTP status codes are three-digit numbers returned by web servers to indicate the result of an HTTP request. The most common status code you'll encounter in successful requests is '200 OK'.
#Verification of Success: 
A status code of 200 OK indicates that the server successfully processed the request, and the response contains the data you requested. It means the web page was found and retrieved without errors.

#Error Handling: 
If the status code is not 200 OK, it typically indicates an issue with the request or the server's response. For example:
404 Not Found: The requested page was not found on the server.
403 Forbidden: The server refuses to fulfill the request, often due to permissions or authentication issues.
500 Internal Server Error: The server encountered an error while processing the request.

#By checking the status code, you can handle errors gracefully. For example, if the status code is not 200 OK, you can choose to log the error, retry the request, or take appropriate action based on the specific error code.
