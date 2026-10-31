# Task 4 – Netflix Titles Dataset Analysis

## Project Overview

This project focuses on exploring the Netflix Titles dataset to identify content trends, understand the distribution of Movies and TV Shows, and analyze popular countries and genres.

The analysis involves data cleaning, feature engineering, exploratory data analysis (EDA), data visualization, and an exploratory trend prediction.

## Dataset Information

- Dataset: Netflix Titles Dataset
- Original records: 8,807
- Original columns: 12
- Source file: `netflix_titles.csv`

## Project Workflow

### 1. Data Understanding and Cleaning
- Loaded and inspected the Netflix dataset.
- Examined data types and missing values.
- Converted `date_added` into datetime format.
- Filled missing values in `director` and `cast` with "Not Available".

### 2. Feature Engineering
Created the following features:
- `release_decade`
- `is_movie`
- `content_type`
- `date_added_year`

The original `release_year` column was retained for year-wise analysis.

### 3. Exploratory Data Analysis and Visualization

Created visualizations to understand:

- Movie vs TV Show distribution.
- Year-wise content release trends.
- Top 10 genres on Netflix.
- Top 5 countries by content volume.
- Country-wise Movie and TV Show distribution.
- Content distribution by release decade.

### 4. Key Insights

- Netflix contains 6,131 Movies and 2,676 TV Shows.
- Movies account for approximately 69.6% of the dataset.
- The United States leads with 3,690 titles, followed by India with 1,046.
- International Movies is the most frequently listed genre with 2,752 entries.
- The 2010s represent the largest release decade, with 5,927 titles.

### 5. What Does This Mean?

The analysis indicates that Movies make up the majority of Netflix's catalogue. The United States and India are among the leading countries represented in the dataset.

The large number of titles released during the 2010s suggests that this decade contributed substantially to Netflix's available content. The genre distribution also highlights the prominence of international content, dramas, and comedies.

These findings help describe the composition and historical release patterns of the Netflix catalogue.

### 6. Bonus – Trend Prediction

A simple Linear Regression model was used to estimate content counts for the next two years based on historical release-year data.

- 2022: 383 predicted titles
- 2023: 390 predicted titles

These values are exploratory estimates and should not be interpreted as actual Netflix release counts or reliable forecasts.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Deliverables

- Python notebook
- Original Netflix dataset
- Six visualizations
- Key insights and interpretation
- Exploratory trend prediction

## How to Run

1. Download the notebook from this repository.
2. Open it using Google Colab or Jupyter Notebook.
3. Upload `netflix_titles.csv` when prompted.
4. Run the notebook cells sequentially to reproduce the analysis.
