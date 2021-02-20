# Movies-ETL

## Summary

- Performed ETL on several movie datasets to predict popular films for a streaming service 

## Overview

### ETL Function to Read Three Data Files 

- Used knowledge of Python, Pandas, and the ETL process to create a function that reads in the three data files and creates three separate DataFrames.

### Extract and Transform the Wikipedia Data 

- Used Python, Pandas, and the ETL process to extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, using a try-except block to catch errors.

### Extract and Transform the Kaggle Data 

- Used Python, Pandas, and the ETL process, to extract and transform the Kaggle metadata and MovieLens rating data, then converted the transformed data into separate DataFrames. Then, merged the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, merged the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

### Create the Movie Database 

- Used Python, Pandas, the ETL process, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
