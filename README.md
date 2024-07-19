# Strategic Recommendations for Restaurant Stakeholders using Advanced Data Mining Techniques

## Project Overview

This project aims to provide strategic recommendations for restaurant stakeholders in Bengaluru by analyzing restaurant data using advanced data mining techniques. By leveraging algorithms such as Prefixspan, FPGrowth, K-Means Clustering, Gaussian Mixture Model (GMM), and DBSCAN, we explore various dimensions of the dataset to uncover frequent patterns, cluster similar entities, and identify anomalies.

## Dataset Description

The Zomato dataset can be used to analyze restaurant trends and factors impacting ratings. The dataset includes over 12,000 restaurants in Bengaluru, offering insights into popular cuisines, customer preferences, and geographical distribution.

### Column Description

- **url**: The URL of the restaurant on the Zomato website.
- **address**: The address of the restaurant in Bengaluru.
- **name**: The name of the restaurant.
- **online order**: Whether online ordering is available.
- **book table**: Whether table booking is available.
- **rate**: The overall rating of the restaurant out of 5.
- **votes**: The total number of ratings for the restaurant.
- **phone**: The phone number of the restaurant.
- **location**: The neighborhood where the restaurant is located.
- **rest type**: The type of restaurant.
- **dish liked**: Dishes people liked in the restaurant.
- **cuisines**: Food styles.
- **approx cost**: The approximate cost for a meal for two people.
- **reviews list**: List of tuples containing reviews for the restaurant.
- **menu item**: The list of menus available in the restaurant.
- **listed(type)**: The type of meal.
- **listed(city)**: The neighborhood where the restaurant is listed.

## Exploratory Data Analysis (EDA)

Through thorough EDA, the project reveals key trends and distributions within the restaurant data, highlighting popular cuisines, customer demographics, and the impact of different factors on restaurant ratings and preferences.

## Proposed Algorithms

### Prefixspan

Prefixspan is used for mining frequent sequential patterns. It helps in identifying common sequences of dishes liked by customers.

### FPGrowth

FPGrowth is used for mining frequent itemsets. It helps in identifying common combinations of restaurant types and cuisines.

### K-Means Clustering

K-Means Clustering is used for grouping similar restaurants based on features such as location and type. This helps in identifying clusters of restaurants with similar characteristics.

### Gaussian Mixture Model (GMM)

GMM is used for probabilistic clustering. It models the data as a mixture of several Gaussian distributions, capturing complex patterns in the restaurant data.

### DBSCAN

DBSCAN is used for density-based clustering. It identifies clusters of restaurants in dense regions and detects outliers in sparse regions.

## Findings and Recommendations

Based on the findings, the project offers practical recommendations for restaurant owners, marketers, and policymakers. These insights aid in making informed decisions about location selection, menu planning, and customer targeting.

## Future Research Directions

The project opens avenues for further research and experimentation in restaurant data analysis. Future work could explore additional algorithms, feature engineering techniques, and data visualization methods to uncover deeper insights and improve the accuracy of predictions and recommendations.

## Contributors

- 21BCE173 - Jil Padalia
- 21BCE200 - Kadam Patel
- 21BCE203 - Khushi Patel

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
