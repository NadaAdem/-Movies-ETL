# Movies Data - Extract, Transform, Load (ETL)

## Project Overview

The purpose of this project is to create one function that takes in the three files: Wikipedia data, Kaggle metadata, and the MovieLens rating data and performs the ETL process by adding the data to a PostgreSQL database.



## Software
- Python 3.7
- pgAdmin 4.50
- PostgreSQL v13


## Resources (Data)
- [Wikipedia Movie Data ](https://github.com/NadaAdem/-Movies-ETL/blob/main/Resources/wikipedia-movies.json)
- [Kaggle Movie Data:](https://www.kaggle.com/rounakbanik/the-movies-dataset) ( downloaded from Kaggle, only "movies_metadata.csv" and "ratings.csv" in zip file  are used in this project.)




## Results
After clean data and convert the transformed data into separate DataFrames ,then merge them . Finally,the dataframe add  to PostgreSQL and CSV data to a SQL database.        for check rows in each table , run a query as  show in below  on the PostgreSQL database that retreives the number of rows for the movies and ratings .

### Number of rows for the movies table 

![image](https://github.com/NadaAdem/-Movies-ETL/blob/main/Resources/movies_query.png)


### Number of rows for  ratings table 

