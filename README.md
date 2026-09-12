# Google Play Store - EDA & Feature Engineering

This project focuses on Exploratory Data Analysis (EDA), data cleaning, and
feature engineering using the Google Play Store dataset.

The main goal is to transform raw application data into a cleaner and more
useful format for analysis and potential machine learning tasks.

## Dataset

The analysis is performed on the `googleplaystore.csv` dataset.

The dataset contains information about mobile applications, including:

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Android Version

## Data Cleaning & Feature Engineering

Several preprocessing and feature engineering steps were performed:

- Checked dataset structure, data types, and missing values
- Identified and removed an invalid observation
- Converted `Reviews` into a numeric data type
- Cleaned the `Size` column and handled "Varies with device" values
- Removed special characters such as `+`, `,`, and `$`
- Converted `Installs` and `Price` into numeric data types
- Converted `Last Updated` into datetime format
- Extracted `Day`, `Month`, and `Year` as new features
- Checked duplicate applications
- Separated numerical and categorical features
- Cleaned Android version information
- Applied encoding to the `Genres` feature based on mean installs

## Exploratory Data Analysis

The project includes visual and statistical exploration of the dataset.

Some of the analyses include:

- Distribution analysis of numerical features
- Analysis of app type and content rating
- App category distributions
- Total installs by category
- Top 10 categories by number of installs
- Top 5 applications in selected categories
- Analysis of applications with a rating of 5.0

## Visualizations

The analysis uses different visualization techniques including:

- KDE plots
- Count plots
- Bar plots
- Pie charts

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project File

The complete analysis and code can be found in the Jupyter Notebook included
in this repository.

## Author

Gül Karagöz
