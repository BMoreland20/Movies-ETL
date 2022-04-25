Summary:
	For this weeks challenge we aimed to extract data from an external source.  Transform said data to a usable form for our analysis.  Then upload completed transformed data up to a SQL server.  In our case this was to our local machine using PostgreSQL.
	After completing the transformation of all data from Wikipedia and Kaggle and merging into one dataframe we result with the following totals in the movies left int the database and the ratings in the database (see images).


![This is an image]( https://github.com/BMoreland20/Movies-ETL/blob/main/Resources/movies_query.png)


![This is an image]( https://github.com/BMoreland20/Movies-ETL/blob/main/Resources/ratings_query.png)


These both were done with the with the following SQL queries `SELECT COUNT (*) FROM movies` and ` SELECT COUNT (*) FROM ratings`.
	With all of the work done transforming and cleaning our data we can see that we have 6,052 movies in our database for later access whether this is via building a website using API requests so others can use our database or just for “company” use.  We can also see that for our ratings data we have 26,024,289 data points, we can also do the same thing as mentioned above by building a website or use said data for “company” use.
