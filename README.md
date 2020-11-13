# ETL-Project

We extracted data from two major data sources below:
https://www.kaggle.com/noriuk/us-education-datasets-unification-project
This dataset was designed to bring together multiple facets of U.S. education data into one convenient CSV (states_all.csv).
https://www.kaggle.com/mikejohnsonjr/us-counties-diversity-index
This dataset contains diversity of United States counties.
As shown in the Jupyter Notebook file, we first extracted data, cleaned up the data, load the two datasets into SQL, joined the two tables in SQL, and then wrote the data back out into new dataframe. We also made several plots based on the data to examine the association between diversity and study performance (using average math score as a proxy), revenue and study performance. Because the revenue could be significantly impacted by the cost of living in different states, we scraped the HTML data from another website containing information on cost of living in all the US states. Using this data, the revenue per student was adjusted to reflect the difference in cost of living. 
The conclusions suggested by the data have been annotated in the script.
