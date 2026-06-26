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

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
