# Project-3
Stock Market Analysis 2019-2024

# Project Overview

This project aims to 

# Instructions

The code used to answer each of the 4 research questions can be found in the 4 python files: "nicole_analysis.ipynb", "Hugo_analysis.ipynb", _, and _. The original csv and sqlite file can be found in the "Resources" folder, labeled "stock_market_data.csv" and "market.sqlite". The user-driven interaction element can be found in the html file labeled "main.html". Once downloaded and opened, it will take the user to a web page in which several links are available that open separate pages filled with our findings. The code for these html files, as well as the images on these pages, can be found in the "sector_htmls" folder and "Images" folder respectively.

# Documentation of the Database

The data is stored in a sqlite database. We chose this because, along with our comfrotability skill-wise, it is stable, compatible, fast, and easy to work with. The database file format is cross-platform, so we were able to upload our csv file directly without having to manually edit data types or headers, and could easily create and engine to communicate with the database in python.

# ETL Workflow

- Extract

 The dataset was initially downloaded as stock_market_data.csv from the following Kaggle dataset: [2019-2024 US Stock Market Data](https://www.kaggle.com/datasets/saketk511/2019-2024-us-stock-market-data).

- Transform

 We transformed the CSV data by:
     Cleaning: Removal of irrelevant data, handling missing or erroneous values.
     Selection: Filtering the dataset to include only the relevant stocks relative to each analysis

- Load

 The transformed data was then loaded into a market.sqlite database, providing a centralized and consistent data source.
 Each team member used this SQLite database to perform their analysis, ensuring uniformity across individual notebooks and analyses.



# Ethical Considerations

# Data References

The dataset used for this project was the "2019-2024 US Stock Market Data" csv file found on kaggle.
Link: https://www.kaggle.com/datasets/saketk511/2019-2024-us-stock-market-data
