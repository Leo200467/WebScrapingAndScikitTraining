# WebScrapingAndScikitTraining

### This repository contains training files for Webscraping, Pandas and some use of SciKit-Learn.

### Some of the libraries used are:

- [X] Beautiful Soup for webscrapping
- [X] Pandas for Dataframe building, modifications, transformations and data preparation
- [X] SQLite 3 as local database for storing scrapped data

### Overview of files

#### [Scraping Training Notebook](/scraping_training_notebook.ipynb)

This notebook uses Beautiful Soup to scrape data from [Books to Scrape](https://books.toscrape.com/), a sandbox website for scrape training.
The data scraped was books from website catalogue ranging from page 1 until page 50 and can be found [here](/scraping_results2.csv). 
The objective was learn scrapping basics and save data into a database, later, this evolved to a attempt to predict prices.

### [Pandas Training Notebook](/pandas_training_notebook.ipynb)

This notebook was used to advance in the attempt of predicting book prices with scrapped data. 
The objective was to try out methods like Random Forest Regressor to predict book pricing using the following features: number of pages, rating and pricing of other books.
Some models were built, but the result wasn't very good with Mean Absolute Error ranging from $11 to $13. 

### [Exercise Categorical Values](exercise-categorical-variables.ipynb)

This notebook was used in a Kaggle Challenge, Housing Prices Competition for Kaggle Learn. 
The goal was to build and tune a Machine Learning Model for housing price prediction using a dataset provided by Kaggle. 
In this specific lesson, encoding and categorical data were the main subjects. 
The objective was to learn more on pricing prediction methods and feature engineering.

### [Scraping XML to SQLite](scraping_xml_to_sqlite.ipynb) and [SQLite Formating](/SQLiteFormating.ipynb)

Both notebooks were used to learn more on how to work with XML data. Parsing, inserting, modeling and transforming.
Then, pushing the data to SQLite3. 

