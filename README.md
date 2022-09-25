# Scraping Your Favorite Quotes from BrainyQuote using Python

Check out the Jupyter notebook here: https://jovian.ai/snoektim/snoek-quotes-scraping

BrainyQuote is a great resource for browsing through quotes. However, it can be valuable to collect quotes for documentation, inspiration, or for further analysis. On the page https://www.brainyquote.com/topics an overview of all the available topics on the site can be found. In this project we will use web scraping to extract a subset of quotes of interest from this site using the Python libraries Requests and Beautiful Soup.

The goal of this project is: to use web scraping to download all the quotes that belong to a certain topic. As an example, we will focus on the topic 'motivational' in order to find out the steps to be taken. Afterwards, we will derive a set of functions that can subsequently be used to scrape any topic of interest.

The outline is given below:

1. Identify the webpages
2. Download a webpage using Requests
3. Use Beautiful Soup to parse the HTML source code
4. Extract author, quote text and url for each quote on the page
5. Collect the downloaded data into Python lists
6. Extract and combine data from multiple pages
7. Create CSV file with the extracted information
