# Netflix-Data-Analysis
Netflix dataset

In this project:
Netflix Dataset
This Netflix Dataset has information about the TV Shows and Movies available on Netflix till 2021.
This dataset is collected from Flixable which is a third-party Netflix search engine, and available on Kaggle website for free.
___________________________________________________________________________________________________________________________________

Cleaning

Task.1. Is there any Duplicate Record in this dataset ? If yes, then remove the duplicate records.
Task.2. Is there any Null Value present in any column ? Show with Heat-map.
____________________________________________________________________________________________________________________________________

Questions to answer:

1. For 'House of Cards', what is the Show Id and Who is the Director of this show?
2. In which year highest number of the TV Shows & Movies were released ? Show with Bar Graph.
3. How many Movies & TV Shows are in the dataset ? Show with Bar Graph.
4. Show all the Movies that were released in year 2000.
5. Show only the Titles of all TV Shows that were released in India only.
6. Show Top 10 Directors, who gave the highest number of TV Shows & Movies to Netflix?
7. Show all the Records, where "Category is Movie and Type is Comedies" or "Country is United Kingdom".
8. In how many movies/shows, Tom Cruise was cast?
9. What are the different Ratings defined by Netflix?
    9.1. How many Movies got the 'TV-14' rating, in Canada?
    9.2. How many TV Show got the 'R' rating, after year 2018?
10. What is the maximum duration of a Movie/Show on Netflix?
11. Which individual country has the Highest No. of TV Shows?
12. How can we sort the dataset by Year?
13. Find all the instances where : 
    - Category is 'Movie' and Type is 'Dramas'
    - Category is 'TV Show' & Type is 'Kids' TV'


commands use:
info() - Provides basic information about the dataframe.
index - This attribute provides the index of the dataframe.
columns - It shows the name of each column.
dtypes - It shows the data-type of each column.
shape - It shows the total no. of rows and no. of columns of the dataframe
nunique() It shows the total no. of unique values in each column. It can be applied on a single column as well as on whole dataframe.
unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
value_counts() - In a column, it shows all the unique values with their count. It can be applied on single column only.
count() - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on whole dataframe.

duplicate()
dropna()
isnull()
isin()
to_datetime()
dt.year.value_counts() 
str.contains()
str.split()
groupby()
countplot()
min(), max(), mean()

Creating new columns
Creating new data frame
Filtering - single column
Filtering - multiple columns
Fintering with And
Filtering with OR

seaborn - Bar graphs
