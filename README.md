# franchise_a_business


__[Refer to Notebook](https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/b00d9d5b-abc0-4e31-9c99-7bfc3bee29c8/view?access_token=2ae0962fd12ad9b3a061190962d9cf1e18620581e739deb9f84bc0a271aa3825)__ to interact with the map and view the report.

![map](predictions_toronto.png)


__Problem:__ 

There are a lot of factors that can contribute to whether to open a franchise in a neighborhood or not. These factors include demographic (such as size of population, household breakdown etc.), socioeconomic (age range, gender, preferences) and geographical factors.

This report focusses on helping business owners identify the neighborhood where to open a Trader Joe's, an American chain of grocery stores headquartered in Monrovia, California. The report specifically studies geographical locations in California to assess how likely is a certain location with no Trader Joes to be a good investment to open one. A prediction is then made on the city of Toronto to assess the likelihood of each neighborhood being a good location for opening a Trader Joe's store.

This project aims to predict the probability of a certain geographical location that doesnt have a local Trader Joe’s to be a likely Trader Joe’s location. Machine learning models are trained to be able to evaluate a location and to make a prediction for potential new locations for Trader Joe's.


__Data Source:__

- API Geocoder for fetching geo-coordinates of neighborhoods in Toronto and California
- [Canada's open data catalog](https://www.toronto.ca/ext/open_data/catalog/data_set_files/2016_neighbourhood_profiles.csv) for data on 140 different neighborhoods in Toronto
- California's list of neighborhoods
- [Foursquare API](https://foursquare.com) for top trending venues in each neighborhood in California and Toronto

__Python Packages:__
- Arrays and data structures (pandas, geopandas and numpy)
- Web scraping (BeautifulSoup, requests, urllib.request, json geopy)
- Machine Learning (sklearn: metrics, model_selection, preprocessing)
- Visualization (seaborn, folium, atplotlib.pyplot)





