Netflix EDA Using Python
Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix dataset using Python. The analysis focuses on understanding content trends, genres, ratings, release years, and country-wise distribution of movies and TV shows available on Netflix.

Objectives
Clean and preprocess the dataset
Handle missing values
Analyze Netflix content trends
Explore genre distribution
Visualize ratings, release years, and content types
Generate insights using data visualization
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Dataset

The dataset contains information about Netflix Movies and TV Shows including:

Title
Genre
Director
Cast
Country
Release Year
Rating
Duration
Type (Movie/TV Show)
Data Cleaning Steps
Removed duplicate records
Handled missing values
Split genre values into lists
Exploded genres into separate rows
Reset dataframe index

Example:

df['Genre'] = df['Genre'].str.split(', ')
df = df.explode('Genre').reset_index(drop=True)
Key Analysis
Most common genres on Netflix
Distribution of Movies vs TV Shows
Content growth over the years
Top countries producing Netflix content
Rating distribution analysis
Visualizations

The project includes:

Bar Charts
Count Plots
Histograms
Heatmaps
Pie Charts

Conclusion
This analysis provides insights into Netflix content trends and demonstrates the use of Python libraries for data cleaning, transformation, and visualization.

This analysis provides insights into Netflix content trends and demonstrates the use of Python libraries for data cleaning, transformation, and visualization.

Author
