## About the Data used to solve the Business problem:

### First Dataset: List of neighbourhoods in Toronto:

Firstly, I will be using data from a wikipedia page which provides information about list of neighbourhoods in Toronto, Canada. I will be using web scrapping tool BeautifulSoup for extracting the data in the form of a table from this wikipedia page.
This table contains 3 columns: Postal Code, Borough and Neighbourhood.
The link for this wikipedia page: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M .
After preprocessing the table and adding two more columns of Latitude and Longitude of each Neighbourhood, this dataset is ready for use. 
Final DataFrame will have 5 columns: Postal Code, Borough, Neighbourhood, Latitude, Longitude.
And it will contain 103 rows having 103 unique neighbourhoods of Toronto and 5 unique Boroughs.

Here is a screenshot of first five rows of the final dataframe:
![dataframe screenshot](![Monthly prices box plot](https://github.com/vibhor98/SocialCops-Data-Science-Intern-Challenge/blob/master/Images/monthly_prices_boxplot%20.png))

### Second Dataset: List of different venues in the neighbourhoods of Toronto:

This dataset will be formed using the Foursquare API. I will use the Foursquare location data to explore different venues in each neighbourhood of Toronto.
These venues can be any place. For example: Parks, Coffee Shops, Hotels, Gyms, etc. 
Using the Foursquare location data, I can get information about these venues and analyze the neighbourhoods of Toronto easily based on this information.

**In general, I will be using these two datasets to solve the business problem of finding the best place to open a restaurant within Toronto**
