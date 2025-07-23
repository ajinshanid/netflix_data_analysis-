# Netflix Movies and TV Shows Data Analysis

## Overview

This project performs a basic Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset. The dataset contains detailed information about titles available on Netflix, including movies and TV shows, their genres, countries, directors, and other features.

The analysis is designed to give insights into the distribution of content types, popular genres, and countries represented on Netflix. It is implemented using Python libraries such as pandas, matplotlib, and seaborn, and is hosted in an interactive Google Colab notebook for easy access and reproducibility.

You can explore and run the complete analysis here:  
[Netflix Data Analysis Colab Notebook](https://colab.research.google.com/drive/17w4fmKexcDeWiuj2H8_sdcLGv5XRQJyT#scrollTo=QUMXVcJ0AR6b)

## Dataset

- **Source:** [Kaggle: Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File name:** `netflix_titles.csv`
- **Key Features:**
  - `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

## Project Workflow

1. **Import Required Libraries**  
   Load pandas, matplotlib, seaborn for data manipulation and visualization.

2. **Load Dataset**  
   Read the CSV dataset into a pandas DataFrame for processing.

3. **Data Cleaning**  
   Handle missing values (fill or drop nulls), remove duplicates if any, and convert categorical data to appropriate types. This step ensures the dataset is clean, consistent, and ready for accurate analysis.

4. **Initial Data Exploration**  
   Inspect the data’s structure, summary statistics, and verify any remaining data quality issues.

5. **Visualizations and Analysis**  
   - Distribution of content types (Movies vs TV Shows)  
   - Most common genres  
   - Countries with the highest number of titles

## Tools & Environment

- Python 3.x  
- Google Colab (interactive notebook environment)  
- Libraries: pandas, matplotlib, seaborn

## Insights & Future Work

- Investigate trends over time and regional content differences  
- Analyze key contributors like directors or actors  
- Build recommendation systems or conduct sentiment analysis on show descriptions

## How This Project Helps

This project serves as a practical introduction to data cleaning and exploratory data analysis for beginners. It demonstrates the importance of preparing clean data and how visualization can reveal meaningful insights from raw data.

