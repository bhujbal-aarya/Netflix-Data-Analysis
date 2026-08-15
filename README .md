# Netflix Data Analysis

## Project Overview

Exploratory Data Analysis (EDA) of a movie dataset using Python. The project focuses on understanding movie genres, vote averages, popularity, and release-year trends through data cleaning, analysis, and visualization.

## Objectives

- Analyze the movie dataset using Python.
- Identify the most frequent movie genres.
- Categorize and analyze vote averages.
- Identify the most and least popular movies.
- Analyze movie release-year trends.
- Create meaningful visualizations and insights from the data.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset

The dataset contains movie information including:

- Release Date
- Title
- Popularity
- Vote Count
- Vote Average
- Genre
- Original Language
- Overview
- Poster URL

For analysis, the `Overview`, `Original_Language`, and `Poster_Url` columns were removed.

## Data Cleaning & Preparation

The following steps were performed:

1. Loaded the dataset using Pandas.
2. Checked duplicate records and dataset information.
3. Converted `Release_Date` to datetime and extracted the release year.
4. Removed columns that were not required for the analysis.
5. Categorized `Vote_Average` into:
   - Not Popular
   - Below Average
   - Average
   - Popular
6. Split multiple genres into separate values and exploded the dataset so each genre could be analyzed individually.
7. Checked missing values and removed incomplete records.

## Analysis & Visualizations

The project includes analysis of:

- Genre Distribution
- Vote Average Distribution
- Most Popular Movie
- Least Popular Movie
- Release Year Distribution
- Top Years with Most Movies
- Movies Released Over the Years

### Visualizations

The notebook uses:

- Count plots
- Histograms
- Bar charts
- Pie charts
- Line charts

## Key Insights

Based on the analysis:

- **Action** is the most frequent genre, followed by Comedy and Drama.
- **Average** is the largest vote-average category in the analyzed data.
- **Spider-Man: No Way Home** has the highest popularity value in the dataset.
- **An American Tail: Fievel Goes West** has the lowest popularity value in the analyzed data.
- **2021** has the highest number of movies in the dataset, with **1,093** records after the analysis transformations.
- The dataset contains release years ranging from **1937 to 2022**.

## Project Files

```text
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb
├── mymoviedb_fixed.csv
└── README.md
```

## How to Run

### Using Google Colab

1. Upload `Netflix_Data_Analysis.ipynb` to Google Colab.
2. Upload `mymoviedb_fixed.csv` to the Colab session.
3. Run the notebook cells from top to bottom.

### Using Jupyter Notebook

1. Download the project files.
2. Place the notebook and CSV file in the same folder.
3. Install the required Python libraries if needed.
4. Open `Netflix_Data_Analysis.ipynb`.
5. Run the cells sequentially.

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Transformation
- Pandas
- NumPy
- Data Visualization
- Matplotlib
- Seaborn
- Python Data Analysis

## Author

**Aarya Bhujbal**

This project was created as part of a data analytics portfolio to demonstrate practical Python-based data analysis and visualization skills.
