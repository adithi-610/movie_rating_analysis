# movie_rating_analysis
# 🎬 Movie Rating Analysis using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the TMDB 5000 Movie Dataset to analyze movie ratings, popularity, and genres. The objective is to gain meaningful insights from movie data using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

The project includes data loading, preprocessing, cleaning, visualization, and insight generation. It is implemented in **Google Colab** using Python.

---

# 📖 Table of Contents

- Project Overview
- Objectives
- Dataset Information
- Technologies Used
- Project Workflow
- Data Preprocessing
- Exploratory Data Analysis
- Visualizations
- Results and Insights
- How to Run the Project
- Future Improvements
- Folder Structure
- Conclusion
- Author

---

# 🎯 Objectives

The main objectives of this project are:

- Load and understand the movie dataset.
- Clean and preprocess the data.
- Handle missing values.
- Analyze movie ratings.
- Identify the most voted movies.
- Analyze movie genres.
- Create visualizations for better understanding.
- Generate useful insights from the dataset.

---

# 📂 Dataset Information

This project uses the **TMDB 5000 Movie Dataset**.

Dataset Files:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

The datasets contain information such as:

- Movie Title
- Budget
- Revenue
- Genres
- Popularity
- Vote Count
- Average Rating
- Language
- Release Date
- Cast
- Crew

---

# 🛠 Technologies Used

Programming Language:
- Python 3

Libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- AST

Platform:

- Google Colab

---

# 📊 Project Workflow

The project follows these steps:

## Step 1: Import Libraries

The required Python libraries are imported.

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

Step 2: Load Dataset
The movie and credits datasets are loaded into Pandas DataFrames.
movies = pd.read_csv(...)
credits = pd.read_csv(...)

Step 3: Explore the Dataset
The following operations are performed:
Dataset dimensions
Preview of data
Statistical summary
Column information
Functions used:
head()
shape
describe()

Step 4: Data Cleaning
The project performs basic preprocessing by:
Checking missing values
Preparing data for analysis
Parsing the genres column
Missing values are identified using:
movies.isnull().sum()
credits.isnull().sum()

Step 5: Genre Parsing
The dataset stores genres as JSON-like strings.
The Python AST library converts these strings into readable lists.
Example:
Before:
"[{'id':28,'name':'Action'}]"
After:
['Action']
This makes genre analysis much easier.

📈 Exploratory Data Analysis (EDA)

Several analyses are performed.
1. Top 10 Highest Rated Movies
Movies are sorted based on:
vote_average

2.Top 10 movies with the highest ratings are displayed.
Visualization:
Horizontal Bar Chart
Purpose:
To identify movies with the highest audience ratings.

3. Top 10 Most Rated Movies
Movies are sorted using:
vote_count
Visualization:
Bar Chart
Purpose:
To identify movies that received the highest number of audience votes.

5. Genre Analysis
Genres are extracted from the dataset.
The frequency of each genre is calculated.
Top 10 genres are displayed.

Visualization:
Horizontal Bar Chart
Purpose:
To understand which genres are most common in the dataset.
📊 Visualizations
The project contains the following graphs:
1. Highest Rated Movies
Horizontal Bar Chart
Shows top-rated movies based on average rating.
2. Most Voted Movies
Bar Chart
Shows movies with the highest vote count.
3. Most Popular Genres
Horizontal Bar Chart
Displays the frequency of movie genres.

📌 Results and Insights
From the analysis, the following insights were obtained:
Highly rated movies are not always the most voted movies.
Some blockbuster movies receive millions of votes despite having average ratings.
Certain genres such as Action, Drama, Comedy, and Thriller dominate the dataset.
Genre analysis helps understand audience preferences.
Vote count and vote average measure different aspects of movie popularity.

▶️ How to Run the Project
Step 1
Open Google Colab.
Step 2
Upload:
tmdb_5000_movies.csv
tmdb_5000_credits.csv
Step 3
Open the notebook.
Step 4
Run all cells sequentially.
Step 5
View the generated graphs and insights.

📁 Project Structure
Movie-Rating-Analysis/
│
├── movie_rating_analysis.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── README.md
└── images/
      ├── top_rated_movies.png
      ├── most_voted_movies.png
      └── top_genres.png

🚀 Future Improvements
This project can be extended by adding:
Movie recommendation system
Machine Learning prediction models
Interactive dashboard using Streamlit
Genre-wise trend analysis
Revenue vs Budget analysis
Popularity prediction
Release year trend analysis
Cast and director analysis
Sentiment analysis using movie reviews

🎓 Learning Outcomes
After completing this project, the following concepts were learned:
Data Loading
Data Cleaning
Data Preprocessing
Exploratory Data Analysis
Data Visualization
Handling Missing Values
Feature Extraction
Working with JSON-like data
Insight Generation

✅ Conclusion
This project demonstrates the complete workflow of Exploratory Data Analysis (EDA) using the TMDB 5000 Movie Dataset. Through data cleaning, preprocessing, visualization, and analysis, valuable insights into movie ratings, vote counts, and genre distribution were obtained. The project serves as a strong foundation for beginners in Data Science and can be further enhanced with recommendation systems and predictive analytics.

👨‍💻 Author
Name: Sai Adithe
Course: B.Tech – Artificial Intelligence and Data Science
Project: Movie Rating Analysis using Python
Platform: Google Colab
