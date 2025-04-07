# Netflix-Data-Analysis

This project focuses on performing data mining on the Netflix dataset, sourced from Kaggle Netflix Dataset (https://www.kaggle.com/datasets/shivamb/netflix-shows). The dataset contains information about Netflix’s extensive catalog of TV shows and movies, including attributes such as title, director, cast, country, release year, rating, and duration.

**Objectives**:
The primary goals of this project are:

- Data Cleaning: Removing duplicates, handling missing values, and preparing the dataset for analysis.
- Data Exploration: Analyzing patterns and trends related to content type (TV shows and movies), release years, and country-specific data.
- Visualizations: Generating visual insights through bar charts, pie charts, heatmaps, and word clouds.
- Advanced Data Mining: Exploring relationships between directors and actors, performing sentiment analysis on descriptions, and identifying correlations between numeric variables.

**Problem Discussion**:
The key problem addressed in this project revolves around understanding the evolution of Netflix’s content library over time and across different categories, such as TV shows and movies. We aim to answer questions like:

- How has Netflix’s content changed over the years in terms of volume?
- Which countries contribute the most to Netflix’s TV shows and movies?
- What are the most common genres, and how do they vary by region?
- Are there specific trends in content ratings and duration?

By answering these questions, we can gain insights into content distribution, regional preferences, and how Netflix’s catalog has evolved in terms of content type and genre over time. We also aim to explore relationships between directors, actors, and content themes through network graphs and sentiment analysis of content descriptions. These findings will help in understanding Netflix’s approach to content acquisition and its impact on global entertainment trends.

**Steps Involved**
- Data Loading: Importing the Netflix dataset using Pandas.
- Data Cleaning: Identifying and removing duplicate entries and handling null values.
- Exploratory Data Analysis (EDA):
- Understanding the distribution of content by category (TV shows vs. movies).
- Analyzing trends in content release over the years.
- Visualizing the distribution of ratings, genres, and countries.

**Tools and Libraries**
- Pandas: For data manipulation and analysis.
- Seaborn & Matplotlib: For creating visualizations.
- TextBlob: For sentiment analysis.
- NetworkX: For creating network graphs to understand relationships between directors and actors.
