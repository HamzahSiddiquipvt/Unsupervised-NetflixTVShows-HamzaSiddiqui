With more than 83 million subscribers and presence in more than 190
countries, Netflix is the most popular Internet television network in the
world. Its users watch more than 125 million hours of TV and movie
content daily, including original series, documentaries, and feature films.
On almost any screen that is linked to the Internet, members can watch
as much as they want, whenever and wherever. Without interruptions or
obligations, members can play, pause, and resume watching at any time.


In this project, I have done

●1.Exploratory Data Analysis

● 2.Understanding what type content is available in different countries

● 3.Is Netflix increasingly focusing on TV rather than movies in recent years.

● 4.Clustering similar content by matching text-based features

The goal of this project is to classify/group the Netflix shows into certain clusters such that
movie and TV shows that are in the same cluster/group should have similar properties
and/or features, while data points in different groups should have highly dissimilar
properties and/or features.

Detailed workflow:
1. Analyze Data: In this initial step we went to look for different features available and tried to understand the
data. During this stage, we looked for the shape of data, data types of each feature, statistical summary etc.

2. EDA: EDA or Exploratory Data Analysis is the critical process of performing the initial investigation on the
data. So, through this we have observed certain trends and dependencies and drawn certain conclusions
from the dataset that will be useful for further processing.

3. Data Cleaning: Checked duplicated values present in the dataset. After that comes the null value and
outlier detection and treatment. For the null values imputation we simply replace with empty string and
drop some of the null rows then analyze outlier and handling.

4. Textual Data Preprocessing: During this stage, cluster the data based on the attributes: director, cast,
country, genre, rating and description. Data preprocessing include Remove all stop words and punctuation
marks, convert all textual data to lowercase. Stemming to generate a meaningful word out of corpus of
words. Tokenization of corpus and Word vectorization. We used Principal Component Analysis (PCA) to
handle the curse of dimensionality.

5. Clusters Implementation: Use K-Means and Agglomerative Hierarchical clustering algorithms to cluster
the movies, obtain the optimal number of clusters using different techniques.

6. Build Content Based Recommendation System: A content-based recommender system was built using
the similarity matrix obtained after using cosine similarity. This recommender system will display 10
recommendations to the user based on the type of movie/show they watched.

