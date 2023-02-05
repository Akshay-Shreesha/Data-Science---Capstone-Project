# Data-Science---Capstone-Project

The objective of this project is to identify the optimal neighborhoods in Manhattan to set up an Indian restaurant that will attract the most customers. The study focuses on finding neighborhoods that are close to tourist locations, but not in close proximity to other Indian restaurants. The analysis involves exploring the trade-off between the proximity to tourist attractions and the competition from existing Indian restaurants. The final result of the project will provide insights into the advantages of choosing each neighborhood, based on various factors such as the population density, tourist footfall, and the number of existing restaurants. This information will help in making informed decisions for setting up an Indian restaurant in Manhattan, maximizing the chances of success.

### Data

Based on definition of our problem, factors that will influence our decission are:
- number of Indian restaurants in the neighborhood.
- average rent in the neighborhood.
- distance of neighborhood from cultural center of Manhattan i.e Empire State Building.

Our neighborhoods names,latitudes and longitudes was obtained from the newyork.json file dataset. Following data sources will be needed to extract/generate the required information:
- Number of restaurants and their type and location in every neighborhood will be obtained using Foursquare API
- Coordinate of Manhattan, neighborhood will be obtained using Google Maps API geocoding.
- An important part of the study is to also look at affordability. For this purpose I found a dataset with average rents for Manhattan here https://
www.rentcafe.com/average-rent-market-trends/us/ny/manhattan/

### Analysis

The analysis performed in this project includes:
1. Exploratory data analysis
2. Clustering of neighborhoods based on the number of Indian restaurants and rental prices
3. Identification of neighborhoods with low Indian restaurant density and affordable rental prices

### Results and Discussion

Our study aimed to identify the most affordable neighborhoods in Manhattan with limited Indian Restaurant options near the cultural center, the Empire State Building. After analyzing 34 neighborhoods in Manhattan, we found that West Village, Tudor City, and Hudson Yards are potential areas to consider. However, it's important to note that the low presence of Indian Restaurants in these neighborhoods could be due to various reasons such as a smaller Indian American population or zoning restrictions. This study serves as a preliminary research and further investigation is necessary to fully understand the situation.

### Technical Details
The project is implemented in Python and uses the following libraries:
1. Pandas
2. Numpy
3. Matplotlib
4. Folium (for visualizing geographical data)

### Conclusion

The Battle of the Neighborhoods project provides a comprehensive analysis of the best neighborhoods in Manhattan for opening an Indian restaurant by considering the interplay between Indian restaurant density, rental prices, and proximity to the cultural center. This information can be useful for entrepreneurs looking to open an Indian restaurant in Manhattan.

### Usage

To run the code, clone the repository and run the Jupyter Notebook file. Ensure that the required libraries are installed.
