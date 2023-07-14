# OSINT_WebScanner
OSINT_WebScanner

#This code will first import the requests, bs4, and json Python libraries. These libraries will be used to get a web page, to parse the web page, and to parse JSON data.

The get_web_page() function will then be defined. This function will get a web page by making a request to the specified URL. The requests library will be used to make the request.

The extract_data() function will then be defined. This function will parse the web page and extract the data from the page. The bs4 library will be used to parse the web page.

The get_domain_info() function will then be defined. This function will get information about a domain using the DomainTools API. The requests library will be used to make the request.

The main() function will then be defined. This function will call the get_web_page() function, the extract_data() function, and the get_domain_info() function. The data extracted from the web page and the domain information will then be printed to the console.

To run the code, you will need to install the requests, bs4, and json Python libraries. You will also need to obtain a DomainTools API key. You can then run the code by saving it as a Python file and then running the file from the command line. For example, if the file is named OSINT_WebScanner.py, you would run it by typing the following command into the command line:


python OSINT_WebScanner.py



This will run the code and print the domain information and the web page data to the console.

This is just a simple OSINT tool. You can extend this code to do more sophisticated tasks, such as gathering information from social media or searching for leaked data.
