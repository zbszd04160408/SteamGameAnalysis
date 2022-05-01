# SteamGameAnalysis

## Objective
Many people, including us, are game lovers, and we’d like to provide some up-to-date game analysis for other gamers. In this way, we can also learn more about the game market and provide some insights based on game information.

## Problem

      
## Dataset
The data was scraped by ourselves from store.steampowered.com. We saved these data as two datasets: Game_Info.csv and Game_Reviews.csv.
The size of the dataset is over 5GB, we're not able to upload it to Github, therefore, we compressed it and uploaded it to Google Drive.           
[Google Drive Link for the Dataset](https://drive.google.com/file/d/10RXDC5JDqxg8b_qw6K8kK11QxC4madZ9/view?usp=sharing)

## Notebooks
**10-GameInfoCollection.ipynb:** In this notebook, we wrote code for scraping basic information of the games from Steam platform, and stored the data as Game_Info.csv.        
**11-GameReviewsCollection.ipynb:** In this notebook, we wrote code to obtain players' reviews for each game from Steam platform, and store the data as Game_Reviews.csv.     
**20-EDA.ipynb:** We used this notebook to performe exploratory data analysis on the Game_Info dataset to gain a better understanding of the data and tried to find out the columns in the game information that have a potential impact on the game's positive rating by visualizing them.      
**30-CollaborativeFiltering.ipynb:** We used collaborative filtering technique as our first approach to the problem to estimate a user’s rating on a game based on existing ratings.       
**31-ReviewModling.ipynb:** For this part, we used review of games as the only input for transformer models and tried to predict whether the gamers are willing to recommend those games.      
**32-ModelingWithAll.ipynb:** This part is an extension of the previous ReviewModeling approach. Besides the review content, we also would like to use other information of users to make a prediction on whether or not the user will recommend this game.        

## Reference
[Kaggle|Steam reviews - EDA & Word Clouds](https://www.kaggle.com/code/pegahpooya/steam-reviews-eda-word-clouds)
[Machine Learning with Text in PySpark](https://datascience-enthusiast.com/Python/PySpark_ML_with_Text_part1.html)
[Sentiment Analysis with PySpark](https://towardsdatascience.com/sentiment-analysis-with-pyspark-bc8e83f80c35)
[Spark Official Document|MulticlassClassificationEvaluator](https://spark.apache.org/docs/latest/api/python/reference/api/pyspark.ml.evaluation.MulticlassClassificationEvaluator.html)
