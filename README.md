# Coursera_Capstone
In this assignment, neighborhoods in the city of Toronto are explored, segmented, and clustered based on the postal code and borough information.
For the Toronto neighborhood data, a Wikipedia page exists that has all the information we need to explore and cluster the neighborhoods in Toronto. 
The Wikipedia page is scraped, the data is wrangled, cleaned, and read into a pandas dataframe.
Once the data is in a structured format,  the neighborhoods in the city of Toronto are explored and clustered. The addresses are converted into their equivalent latitude and longitude values. Also, the Foursquare API is used to explore neighborhoods. 
The explore function is used to get the most common venue categories in each neighborhood, and then this feature is used to group the neighborhoods into clusters. The k-means clustering algorithm completes this task. Finally, the Folium library helps us to visualize the neighborhoods in Toronto and their emerging cluster.
