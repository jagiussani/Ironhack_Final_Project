# Ironhack_Final_Project
## Movie recommender

![image](https://github.com/dablancog/Ironhack_Final_Project/assets/71353228/d81de271-92da-47a8-8719-039bf5c11b7a)

**Project objective:** 
Develope a film recommendor and practice using NLP models.

**Description:**
The user can input a movie description. Given the synopsis of american films, our model is able to suggest similar movies.

**Outline of the project:**

**- Day 1:**
Data collection and EDA:**

We are using the following dataste from Kaggle:
IMDB Movies - All Categories
https://www.kaggle.com/datasets/drshashikanthvydyula/imdb-movies

If needed, and time allows, we will collect additional movie synopsis data from a website like IMDB or Rotten Tomatoes. We use web scraping techniques to extract the synopsis for a large number of movies.

**- Day 2:**
**- Data cleaning and preprocessing:** 
Filling NaNs, normalizing columns.
Preprocess the synopsis data by removing stop words, punctuations, and special characters. Convert the text data to a numerical format using techniques like TF-IDF (NLP).

**- Day 3:**
**- Clustering:** 
Cluster the movie synopses into different groups using a clustering algorithm like K-Means. We will experiment with different numbers of clusters to see which one works best.

**- Day 4 y 5:**
**- Evaluating different models**
Comparing error metrics of the different clustering models and improve their performance.
Analyze the clusters to see if they make sense. Look for patterns and themes in the synopses within each cluster.

**-Day 6**
**- Movie recommendation system:** 
Develop a recommendation system that suggests movies based on the user's input. The system can use the cluster information to recommend movies that are similar to the user's preferences.

**-Day 7**
**- Presentation:**
Make a presentation (Tableau - desired) to visualize the clusters, main findings and the recommendation results using graphs and charts.
