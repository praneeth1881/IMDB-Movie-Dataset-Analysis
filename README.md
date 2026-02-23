


# IMDB Movie Data Analysis (ETL + EDA)

## About the Project
In this project, I worked on an IMDB movie dataset and built a small ETL pipeline using Python. The idea was to take raw movie data, clean it properly, apply some business rules, and then explore it to get useful insights.
The final dataset is clean and structured, so it can be easily used for dashboards or database storage.


---

## What's Inside

- imdb_movies.csv
 → Raw dataset that I started with

- IMDB Movie Business Rules and dashboard_problems statements.txt
 → Contains the rules and questions I followed while analyzing

- imdb_ddl.sql
 → SQL script to create tables for storing the cleaned data

- imdbmovies_etl.ipynb
 → Main notebook where all the work happens (ETL + analysis)

---

## Tools & Libraries


- Python

- Pandas

- Matplotlib

- SQLAlchemy

- Jupyter Notebook

---

## Setup Instructions

Create a virtual environment:

```bash
python -m venv .venv
.\.venv\Scripts\activate
```

Install required packages:

```bash
pip install pandas matplotlib sqlalchemy jupyter
```

---

## How to Run the Project

1. Open the notebook:
   ```bash
   imdbmovies_etl.ipynb
   ```

2. Run all cells sequentially to:
   - Load raw data
   - Clean and transform the dataset
   - Apply business rules
   - Generate visualizations

---

## What I Did (ETL Process)

## Cleaning the Data
- Handling missing values  
- Removing duplicates  
- Standardizing column names  
- Parsing date columns  
- Normalizing numeric fields  

### Applying Bussiness Rules
- Applying validation logic  
- Deriving calculated fields  
- Aggregations for analytics  
- Filtering and transformation as per defined rules  

### Exploring The Data
- Movie release trends  
- Genre analysis  
- Rating distribution  
- Revenue analysis  

---
## Dashboards and Visualizations

### Average Rating by Genre
![Average Rating by Genre](Reports/Average%20Rating%20by%20Genre.png)

### Budget vs Gross Correlation
![Budget vs Gross Correlation](Reports/Budget%20vs%20Gross%20Correlation.png)

### Most Profitable Genre
![Most Profitable Genre](Reports/Most%20Profitable%20Genre.png)

### Top 10 Highest Grossing Movies by Year
![Top 10 Highest Grossing Movies by Year](Reports/Top%2010%20Highest%20Grossing%20Movies%20by%20Year.png)

### Top 5 Directors by Average Ratings
![Top 5 Directors by Average Ratings](Reports/Top%205%20Directors%20by%20Average%20Ratings.png)


## Project Objective

This project demonstrates:

- Practical ETL workflow implementation  
- Business-rule-driven data transformation  
- Data validation and cleaning techniques  
- Analytical insights generation  
- End-to-end pipeline from raw dataset to database-ready format
