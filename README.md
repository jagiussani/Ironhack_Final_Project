# Ironhack_Final_Project
Ironhack bootcamp final project. Movie recommender.
![image](https://github.com/dablancog/Ironhack_Final_Project/assets/71353228/c93e2bf7-a0ec-4276-a11d-c5c8db81f1f5)

Project objective: 
Create a film recommendor and practice using NLP models.

Description:
The user can input a movie description. Given the synopsis of american films, our model is able to suggest similar movies.

Outline of the project:
- Data collection: 
Collect movie synopsis data from a website like IMDB or Rotten Tomatoes.We use web scraping techniques to extract the synopsis for a large number of movies.

- Data cleaning and preprocessing: 
Preprocess the data by removing stop words, punctuations, and special characters. Convert the text data to a numerical format using techniques like TF-IDF (NLP).

- Clustering: 
Cluster the movie synopses into different groups using a clustering algorithm like K-Means. We will experiment with different numbers of clusters to see which one works best.

- Exploratory data analysis: 
Analyze the clusters to see if they make sense. Look for patterns and themes in the synopses within each cluster.

- Movie recommendation system: 
Develop a recommendation system that suggests movies based on the user's input. The system can use the cluster information to recommend movies that are similar to the user's preferences.

- Visualization: Visualize the clusters and the recommendation results using graphs and charts.
