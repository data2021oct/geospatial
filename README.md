# geospatial

![](https://img1.picmix.com/output/stamp/normal/8/9/6/8/1898698_2f457.gif)

## Objetive:

- Find a location for a new gaming company based in some of this directives:
    - Designers like to go to design talks and share knowledge. There must be some nearby companies that also do design.
    - 30% of the company staff have at least 1 child.
    - Developers like to be near successful tech startups that have raised at least 1 Million dollars.
    - Executives like Starbucks A LOT. Ensure there's a starbucks not too far.
    - Account managers need to travel a lot.
    - Everyone in the company is between 25 and 40, give them some place to go party.
    - The CEO is vegan.

## Method:

- Study mongodb collection "companies" to chose three locations
- Conect to Foursquare to see if the locations chosen met the criteria of the direcitves
- Compare the cities and see if any one of them is better than the rest to set the new company.

## Structure:

- 3 notebooks:
    - study of companies
    - conection to Foursquare and comparation
    - 3 maps of the cities with all the venues that match the critearias (use [nbviewer](https://nbviewer.org/github/data2021oct/geospatial/blob/main/notebooks/mapas.ipynb) to see it)
- folder Data:
    - stores data i have created during the analysis:
        - venues_df.csv contains all the venues i have found in Foursquare and i have used it to load the information in the maps
        - geo_venus.csv contains all the data in geoDataFrame format