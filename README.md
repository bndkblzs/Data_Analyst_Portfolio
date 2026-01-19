# Data Analyst Portfolio – Movies Analysis

This project presents an exploratory data analysis (EDA) of a movie dataset using Python.  
The goal is to identify patterns and relationships between audience scores, Rotten Tomatoes scores, worldwide gross revenue, and profitability.

## Project Overview

The analysis focuses on:
- Audience scores vs Rotten Tomatoes scores  
- Worldwide gross revenue distribution (original scale and log-transformed scale)  
- Profitability vs worldwide gross  
- Genre-level aggregation of audience and critic scores  
- Bivariate relationships between key variables  

Log-scale transformations are applied where necessary to handle skewed revenue distributions and improve interpretability.

## Dataset

The dataset contains information about movies, including:
- Audience score (%)  
- Rotten Tomatoes score (%)  
- Worldwide gross revenue  
- Profitability  
- Genre  

Source: movies.csv

## Technologies Used

- Python  
- pandas  
- numpy  
- matplotlib  

## Files in This Repository

- `movies.csv` – raw dataset  
- `movies_analysis_en.ipynb` – analysis notebook (English)  
- `movies_analysis_hun.ipynb` – analysis notebook (Hungarian)  

## Key Insights

- Audience scores and Rotten Tomatoes scores show a moderate positive relationship.  
- Worldwide gross revenue is highly right-skewed; log transformation improves interpretability.  
- Revenue alone does not strongly explain profitability differences across films.  
- Genre-level analysis reveals differences in average audience and critic reception.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/bndkblzs/Data_Analyst_Portfolio.git
