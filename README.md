# IMDB-Movie-Data-Visualization-
Exploratory Data Analysis 

I have used the data for the 100 top-rated movies from the past decade along with various pieces of information about the movie, its actors, and the voters who have rated these movies online . I have utilized the numpy , pandas , seaborn and matplotlib library of Python . 

I have performed the following steps to complete an EDA :-

1. Data preparation : - 
    a) These numbers in the budget and gross columns are too big, compromising its readability. Converting the unit of the budget and gross columns from $ to million$.
    b) Created a new column called profit which contains the difference of the two columns: gross and budget .Sorting the dataframe using the profit column as reference.Extracting the top ten profiting movies in descending order and store them in a new dataframe - top10.
    c) Extracting the movies with a negative profit and storing them in a new dataframe - neg_profit
    d) MetaCritic score is on a scale of 100 whereas the IMDb_rating is on a scale of 10 hence converting the MetaCritic column to a scale of 10.
    e) Combining the dataframes by genre 
