# Movies ETL
This repository contains code that extracts movie data, creates Pandas DataFrames, and loads data into an SQL database. The ETL_function_test file tests if a function can create a DataFrame. The ETL_clean_wiki_movies file then builds off this code to create a DataFrame out of movie data from Wikipedia. ETL_clean_kaggle_data further builds on this to merge additional data from Kaggle and MovieLens to this DataFrame while removing redundant and unnecessary columns and rows. Then in the ETL_create_database file, the function also creates this DataFrame and then loads it into an SQL database along with movie ratings data.