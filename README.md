# Zomato-Restaurant-Data-Analysis
Analysis of a Zomato dataset to identify top-rated restaurants and popular locations in Bengaluru, using Python, Pandas, and Matplotlib. Visualizations explore ratings, votes, and restaurant quality.


# Zomato Restaurant Data Analysis

[![Python](https://img.shields.io/badge/python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/)

This repository contains a **Jupyter Notebook** analyzing a publicly available Zomato restaurant dataset from Kaggle. The project focuses on **data cleaning, preprocessing, exploration, and visualization** to extract actionable insights about restaurant popularity and location-based trends in India, specifically Bengaluru.

---

## Dataset

The dataset used in this project is publicly available on Kaggle:  
[Zomato Dataset by Rajesh Rampure](https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset)  

- Contains restaurant details including name, location, votes, ratings, approximate cost, and other features.

---

## Project Overview

The main objectives of this project are:

- Clean and preprocess restaurant data  
- Standardize column names and fix encoding issues  
- Handle missing values and duplicates  
- Explore ratings, votes, and restaurant locations  
- Identify top-rated restaurants and popular locations  
- Visualize relationships between ratings and votes  

---

## Key Features & Visualizations

- **Column Standardization:** Ensured consistent naming and encoding across all textual columns.  
- **Data Cleaning:** Removed non-ASCII characters and handled missing values.  
- **Duplicate Handling:** Ensured no duplicate restaurant entries interfere with analysis.  
- **Top 10 Locations by Average Rating:** Identifies areas with quality restaurants.  
- **Top 10 Restaurants by Total Votes:** Highlights restaurants with credible and reliable ratings.  
- **Scatter Plot: Votes vs. Ratings:** Shows how vote count relates to rating stability and credibility.  

---

## Insights

- High average ratings indicate areas with quality restaurants.  
- Total votes help measure the credibility of ratings; more votes reduce the effect of biased reviews.  
- Scatter plots reveal the relationship between popularity (votes) and quality (ratings), helping identify trustworthy top-performing restaurants.  

---

## Tech Stack

- **Python 3.x**  
- **Pandas** for data manipulation  
- **Matplotlib** for visualization  
- **Jupyter Notebook** for analysis  

---

## Usage

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
