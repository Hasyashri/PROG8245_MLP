# Data Engineering & EDA Workshop - PROG8245

This project demonstrates the complete data engineering and exploratory data analysis (EDA) process using Python, Pandas, PostgreSQL (Neon.tech), and Faker-generated synthetic data.

## Objectives
- Set up and connect to a cloud-based Postgres database (Neon.tech).
- Generate and insert synthetic employee records using faker
- Perform data cleaning, transformation, and feature engineering.
- Normalize numeric data.
- Create visualizations for key business insights.

## Project Structure
- `MLP_LAB_3.ipynb`: Main Jupyter Notebook with code, markdown, and visualizations.
- `requirements.txt`: Dependencies used in the notebook.
- `.gitignore`: Prevents sensitive and unnecessary files from being committed.

## Requirements
- Python 3.8+
- PostgreSQL-compatible database (used Neon.tech)
- Internet connection (for cloud DB and Faker)

## Visualizations
- Grouped bar chart: Average Salary by Position and Start Year
- Heatmap: Average Salary by Department and Position
- Scatterplot with Tradeline: salary versus start year
- Multi-facet Bar chart: Average salary trends across different departments over the years

## Instructions
1. Clone the repo
2. Create a virtual environment `python -m venv venv`
3. Install dependencies: `pip install -r requirements.txt`
4. Replace credentials in `conn_str` with your Neon database connection
5. Run the notebook step-by-step

## Reference
I used chatgpt and https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html for the coding.
