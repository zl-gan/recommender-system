# Building a Recommendation System for Users Using The Movie Dataset

## Introduction

The movie industry is a high-risk and high-reward business that depends on the viewers' tastes and preferences. Online movie platforms provide a large database of movies with various information such as ratings, reviews, genres, keywords, etc. The study aims to apply data mining and machine learning techniques to analyze the movie dataset and build a recommendation system for users.

## Data Understanding and Integration
The movie dataset used in this study is available on [Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset). \
The dataset consists of metadata on over 45000 movies, ratings from 270000 users, and keywords for each movie. \
The dataset was originally collected to use with the MovieLens ratings for creating recommender systems.

## Recommender Systems

Recommender systems are information filtering systems that mitigate information overload on users by filtering vital information out of a large amount of dynamically generated information according to user’s preferences, interest, or observed behavior on an item. \
The aim of recommender systems is to provide users with personalized content and services. \
In this study, three different recommender systems are modeled based on the movie dataset, namely collaborative filtering, content-based, and hybrid recommender systems.

### Collaborative filtering recommender system
This type of recommender system uses the user ratings data to find the similarity between users or items and recommend the most similar items to the users. It can be memory-based or model-based. It performs well for the movie dataset but suffers from the cold start problem.

### Content-based recommender system
This type of recommender system uses the metadata of the movies such as genres, keywords, and overview to create user profiles and recommend the items that match the user preferences. It uses the TF-IDF method and cosine similarity to measure the similarity. It does not require user ratings but suffers from the overspecialization problem.

### Hybrid recommender system
This type of recommender system combines different recommendation techniques such as collaborative filtering and content-based to provide better recommendations and avoid the limitations of pure recommender systems. It can use different hybridization methods such as weighted, switching, mixed, feature combination, cascade, feature augmentation, or meta-level.

## Performance measures of recommender systems
This study uses various metrics to evaluate the recommender systems such as precision, average precision, mean average precision, recall, and area under curve. These metrics measure how accurate and relevant the recommendations are for the users. 

## Discussion and Analysis
The study found that the collaborative filtering recommender performs the best, followed by the hybrid and content-based recommender systems.
The collaborative filtering recommender system is best suited to be used as the recommender system modeled upon the movie rating dataset to recommend movies to users based on their previous interactions.

## Conclusion
According to the document: Recommender systems are a useful tool in suggesting recommendations to the general users. By providing users with personalized content and services, recommender systems are able to increase user satisfaction and loyalty, which in turn increases the revenue of a company. In this case study, three different recommender systems are modeled based on the movie dataset, namely collaborative filtering, content-based, and hybrid recommender systems. The models evaluated using metrics such as recall, precision, mean average precision, and area under curve. Based on those metrics, it could be observed that the collaborative filtering recommender performs the best, followed by the hybrid and content-based recommender systems. Recommender models can be used in various industries such as e-commerce, retail, and video streaming sites in order to keep customers and users engaged and entertained while using the services. 
