Web Scraping Project: Extracting Data from Wikipedia

Project Overview

This project involves web scraping a table from a real-world website: Wikipedia's List of largest companies in the United States by revenue. Using Python and the Pandas library, the table titled "List of the largest public / publicly traded companies" was extracted and converted into a structured CSV file for further analysis.

Objectives

Extract data from a live website using Python.

Parse and process the HTML content to identify and extract relevant information.

Convert the extracted data into a structured format (CSV).

Tools and Technologies Used

Python: The core programming language for this project.

BeautifulSoup: For parsing and navigating the HTML content.

Requests: For fetching the HTML content of the website.

Pandas: For data manipulation and exporting to CSV format.

Jupyter Notebook: For developing and testing the code interactively.

Project Workflow

Fetching the Website Content:

Used the requests library to fetch the HTML content of the Wikipedia page.

Parsing HTML with BeautifulSoup:

Analyzed the structure of the webpage to locate the required table.

Extracted the <table> element containing the data of interest.

Data Extraction:

Retrieved the headers (<th> elements) and rows (<tr> elements) from the table.

Processed and cleaned the extracted data to ensure consistency.

Data Transformation:

Converted the data into a Pandas DataFrame for better manipulation and visualization.

Exporting Data:

Saved the final DataFrame as a CSV file for future use.

Skills Gained

Through this project, I developed and enhanced the following skills:

1. Web Scraping

Understanding and navigating HTML structure to locate specific elements.

Extracting and parsing data using BeautifulSoup.

2. Data Wrangling

Cleaning and transforming raw HTML data into structured formats.

Handling missing or inconsistent data.

3. Python Programming

Writing efficient and reusable code to automate data extraction.

Utilizing libraries such as requests, BeautifulSoup, and pandas.

4. Data Analysis Tools

Working with Pandas for data manipulation.

Exporting data to CSV format for further analysis.

5. Problem-Solving and Debugging

Addressing challenges such as dynamic website elements or inconsistent data formatting.

Results

The extracted data was successfully converted into a CSV file, providing a structured and clean dataset containing:

Rank

Name

Industry

Revenue (USD millions)

Revenue Growth

Employees

Headquarters

How to Use This Project

Clone this repository to your local machine:

git clone https://github.com/your-username/repository-name.git

Install the required Python libraries:

pip install -r requirements.txt

Run the script to scrape data and generate the CSV file:

python scrape_wikipedia.py

The CSV file will be saved in the project directory.

Future Improvements

Implement dynamic scraping techniques to handle JavaScript-rendered content.

Add error handling to manage unexpected changes in the website structure.

Visualize the extracted data using tools like Matplotlib or Seaborn.

Acknowledgements

Data sourced from Wikipedia.

Inspiration and guidance from the open-source Python community.

Feel free to reach out or contribute to this project! Feedback and suggestions are always welcome.

