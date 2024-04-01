# **Web scraping and data wrangling with Beautiful Soup and Pandas**
In data science, web scraping is the process of extracting data from websites, which is useful for collecting vast amounts of information quickly or analyzing real-time data. This data is typically extracted in an unstructured HTML format, so it must be converted into a structured form, such as a pandas DataFrame.

In this project, Beautiful Soup was used to scrape data from a Wikipedia article on the top companies by revenue in the US. The extracted data was then inserted into a pandas DataFrame for wrangling (manipulating the data to make it suitable for analysis).

URL to the Wikipedia article: https://en.wikipedia.org/wiki/List_of_largest_companies_by_revenue

## Web scraping process
* Obtaining the html code of the article
* Using Beautiful Soup to work with the code as a text
* Finding the table of interest in the code
* Extract the information from each of the columns
* Inserting the information into a pandas DataFrame

## Data wrangling process:
* Manipulating and transforming string values into a numerical category when appropriate
* Splitting columns with more than one value in them
* Renaming columns for clarity
