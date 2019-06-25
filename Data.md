## About the Data used to solve the Business problem:

### First Dataset: List of neighbourhoods in Toronto:

Firstly, I will be using data from a wikipedia page which provides information about list of neighbourhoods in Toronto, Canada. I will be using web scrapping tool BeautifulSoup for extracting the data in the form of a table from this wikipedia page.
This table contains 3 columns: Postal Code, Borough and Neighbourhood.
The link for this wikipedia page: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M .
After preprocessing the table and adding two more columns of Latitude and Longitude of each Neighbourhood, this dataset is ready for use. 
Final DataFrame will have 5 columns: Postal Code, Borough, Neighbourhood, Latitude, Longitude.
And it will contain 103 rows having 103 unique neighbourhoods of Toronto and 5 unique Boroughs.

Here is a screenshot of first five rows of the final dataframe:
![dataframe screenshot](https://github.com/akshatsinghal92/Coursera_Capstone/blob/master/Images/df_1.JPG)

For example, above we can see that first row contains a Borough named **North York** which contains one neighbourhood named **Parkwoods** and has a Postal code of **M3A**. The geographical coordinates of this neighbourhood is **(43.753259,-79.329656)**.

### Second Dataset: List of different venues in the neighbourhoods of Toronto:

This dataset will be formed using the Foursquare API. I will use the Foursquare location data to explore different venues in each neighbourhood of Toronto.
These venues can be any place. For example: Parks, Coffee Shops, Hotels, Gyms, etc. 
Using the Foursquare location data, I can get information about these venues and analyze the neighbourhoods of Toronto easily based on this information.

We will use the geographical coordinates from above dataset to generate this Location dataset.
Here is the screenshot of the sample dataset:

![dataframe screenshot1](https://github.com/akshatsinghal92/Coursera_Capstone/blob/master/Images/df_3.JPG)

For example, First row contains Neighbourhood named **Battery Park city** with its respective 5 most common venues which are Park, Coffee shop, Hotel, Gym and Memorial site.


**In general, I will be using these two datasets to solve the business problem of finding the best place to open a restaurant within Toronto**
