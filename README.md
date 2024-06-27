# Movie-Recommendation-System
![Power BI](https://github.com/Ndivhoniswani/Movie-Recommendation-System/blob/main/ShowMax%20Image.png)

In the vast world of movies, finding the perfect film to watch can be a daunting task. This is where recommendation systems come into play, making the process much smoother and enjoyable for users.

### Table of Contents
- [Data Overview](#Data-Overview)
- [Understanding Collaborative Filtering](#Understanding-Collaborative-Filtering)
- [Data Source](#Data-Source)
- [Tools](#Tools)
- [Building the Recommendation System](#Building-the-Recommendation-System)
- [Results](Results)
- [Recommendation]([Recommendation)
- [Usage](Usage)

### Data Overview
This dataset consists of several million 5-star ratings obtained from users of the online MovieLens movie recommendation service. The MovieLens dataset has long been used by industry and academic researchers to improve the performance of explicitly-based recommender systems, and now you get to as well!

For this Predict, we'll be using a special version of the MovieLens dataset which has enriched with additional data, and resampled for fair evaluation purposes.

### Understanding Collaborative Filtering!
![Power BI](https://github.com/Ndivhoniswani/Movie-Recommendation-System/blob/main/Collaborative%20Filtering%20Image.png)

Collaborative Filtering relies on user preferences to make recommendations. For movies, it uses data from user ratings and behaviors. The system identifies similar users and suggests movies that those users liked, creating personalized recommendations based on shared interests.


### Data Source
- genome_scores.csv - a score mapping the strength between movies and tag-related properties.
- genome_tags.csv - user assigned tags for genome-related scores
- imdb_data.csv - Additional movie metadata scraped from IMDB using the links.csv file.
- links.csv - File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
- sample_submission.csv - Sample of the submission format for the hackathon.
- tags.csv - User assigned for the movies within the dataset.
- test.csv - The test split of the dataset. Contains user and movie IDs with no rating data.
- train.csv - The training split of the dataset. Contains user and movie IDs with associated rating data.

**Note: Note that the dataset will not be available here, due to copywrite issues.


### Tools
- Python
- Recommender System: Collaborative Filtering
- Jupyter Notebook


### Building the Recommendation System
To implement Collaborative Filtering, we’ll use a dataset of movies, train, test and their features. Popular Python libraries like Pandas, Scikit-learn and the powerful Suprice library will be employed to preprocess the data and build a recommendation model. The key steps include:

1. EDA: View merged dataset and the are no missing values and the data types are in the correct order.
2. Data Preprocessing: Cleaning and organizing the movie dataset.
   
   ![Power BI](https://github.com/Ndivhoniswani/Movie-Recommendation-System/blob/main/Preprocessing%20data.png)
3. Building a Model with Collaborative Filtering.
   
   ![Power BI](https://github.com/Ndivhoniswani/Movie-Recommendation-System/blob/main/Model.png)
4. Predictions on the test dataset
   
   ![Power BI](https://github.com/Ndivhoniswani/Movie-Recommendation-System/blob/main/Predict%20on%20test%20dataset.png)

### Results
We used the powerful Surprise Library to build a collaborative filter based on single value decomposition. The RMSE obtained was less than 2, see below and the engine gave estimated ratings for a given user and movie.

![Power BI](https://github.com/Ndivhoniswani/Movie-Recommendation-System/blob/main/Hackathon%20Score.png)

### Recommendation


### Usage

