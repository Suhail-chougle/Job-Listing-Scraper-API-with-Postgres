# Job-Listing-Scraper-and-Flask-API-for-Reed.co.uk

This Python project utilizes Beautiful Soup to efficiently scrape job listings from Reed.co.uk, extracting essential details such as title, 
location, description, technologies (e.g., nodejs, python), posted date, company name, and salary for approximately 50 listings. Subsequently, 
it implements a robust Flask API that supports pagination, sorting, and unit testing. Leveraging a Postgres database, the API allows seamless 
access to job details based on technology and location preferences. The project also includes API documentation, and to prevent site overload, 
requests are throttled to less than 20 requests per minute. Organized into three Jupyter notebooks, the project facilitates easy understanding and navigation.

Details: 
The web scraper collects the follwing data:

1. Title
2. Location
3. Description
4. Technologies like nodejs,python etc
5. Posted date
6. Company name
7. Salary

for about 50 job listings and subsequently writes an api to fetch these job
details by technology and location.

Functional operations:
● Api supports pagination and sorting.
● Python used for this task
● Database used is Postgres
● Supports unit testing

Included:
1. API documentation
2. Throttle requests to less than 20 req per min so that site is not affected by
the task

The folder contains 3 jupyter notebooks:
1. Code-Flask_api_Postgres - Includes jupyter notebook which writes a python script for Flask API 
			     and connects it to Postgres database
2. Code-Scraping_Postgres - Includes jupyter notebook which writes a python script using Beautiful Soup to scrape 
			    job listings from Reed.co.uk and store it in a table in Postgres 
3. Code-Unit_testing - Includes jupyter notebook which writes a python script for unit testing the endpoints of the API and sorting









