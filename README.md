# Movies - Extract, Transform, Load

## Resources
* Data Source: ratings.csv; movies_metadata.csv; wikipedia-movies.json
* Software: Python, Jupyter Notebook, Pandas, PostgreSQL, pgAdmin

## Analysis
Amazing Prime needs us to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. By refactoring previously used code, we'll create one function that takes in the three files — Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
