# Restaurants Recommendation Location-Based: “Cold Start”
This project presents a solution to the user cold-start problem in recommender systems by implementing geographic clustering methods on Yelp restaurant data.
The "cold-start" problem, is where new users without prior activity or preferences pose a challenge in delivering personalized and relevant recommendations.
Traditional approaches relying on historical data fall short for these users, emphasizing the need for innovative solutions.
Our project aims to address this issue using geospatial data available within Yelp's extensive collection of restaurant information.
## Project Description
We implemented and compared clustering methods: K-means, hierarchical clustering and DBSCAN, selecting the optimal method via silhouette scores.
Our experimentation assessed three core aspects: precise geographic clustering of restaurants, quality of recommendations within clusters focusing on high-rated restaurants, and the response time.
The chosen clustering approach enabled us to provide users with immediate quality-focused recommendations based on their location, improving user engagement and trust in the system.
## Data
API KEY= to try this code you will need to inser your API KEY from Yelp. for help: https://docs.developer.yelp.com/docs/getting-started.
## Restrictions
Github does not allow to display "folium" type maps as there are in this work.
In order to see the maps, screenshots were taken to the appendix attached to this project "Appendix to Jupyter Notebook".
In order to see the maps interactively, the code must be run on a suitable environment.
