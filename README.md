# Analysis of Television Shows on Stream platforms
#### Bryan Kolano
#### November 11, 2022

### Data Description
The data for this analysis comes from user Ruchi Bhatia who submitted this stream dataset on [Kaggle.com](https://www.kaggle.com/datasets/ruchi798/tv-shows-on-netflix-prime-video-hulu-and-disney).

The dataset consists 5,368 television shows across four stream platforms: Netflix, Disney +, Hulu, and Amazon Prime.  370 of the shows are hosted on multiple streaming platform.

The original dataset consists of show name, debut year, Internet Movie Database (IMDb) rating, Rotten Tomatoes (RT) rating, and individual boolean columns for which platform a given show is hosted on.

Analysis Documents in repo:

1. Exploratory data analysis: visual explorations into the original dataset
- This notebook visually explores the dataset the have an initial understanding of the data.
2. Webscraping of IMDb: enrichment of original data adding show themes/ tags as well of IMDb show description.
- This notebook takes the original dataset and then grabs the shows theme tags and show description from IMDb and appends that information into the original dataset.
3. Recommender: two different explorations into a TF-IDF show recommender and a transformers recommender.
- This notebook takes the enhanced dataset from the scraping notebook and then creates two different recommender models.  A user can input a streaming TV show, and each of the models will return recommendations based on the inputted show's IMDB description.  One Model uses TF-IDF to create embeddings and the other uses transformers to create the embeddings.



