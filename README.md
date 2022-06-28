# movies-ETL
### The purpose of this analysis was to create an automated pipeline that performs the ETL process we completed in module 8 for movie company Amazing Prime. We refactored the code to create a function that extracts in Wikipedia data, Kaggle metadata, and MovieLens rating data, transforms the data, then loads it into an SQL database. 

* P.S. the movie table in SQL may show 6051 instead of 6052 because one fault row was removed (row 3607 of movies_df, AKA the 2006 outlier in module 8)
