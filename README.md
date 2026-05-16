<h1 align="center">🍿📺 Netflix Movies & TV Shows Data Analysis Project 🎬📊</h1>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/75/Netflix_icon.svg" width="200">
</p>
<kbd>![Netflix Banner](https://upload.wikimedia.org/wikipedia/commons/7/75/Netflix_icon.svg)</kbd>

---

# 🏷️ Overview
Welcome to my **Netflix Data Analysis Project**, where I performed a complete **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset from Kaggle using Python.

This project focuses on cleaning raw Netflix data, handling missing values, transforming columns, analyzing trends, and visualizing insights to better understand Netflix’s content distribution.

The goal of this project is to strengthen my **Data Analytics / Data Science fundamentals** by applying:
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Filtering
- GroupBy Analysis
- Visualization
- Trend Analysis

---

# 🎯 Project Objective
- Clean and preprocess Netflix dataset
- Handle missing values and duplicate records
- Analyze Movies vs TV Shows distribution
- Discover top countries, genres, directors, and actors
- Explore release year and Netflix growth trends
- Perform duration analysis
- Visualize insights using charts
- Build a beginner-friendly end-to-end data analytics project

---

# 📚 Dataset
**Dataset Source:** Netflix Movies and TV Shows Dataset from Kaggle

### Dataset includes:
- Title
- Type (Movie / TV Show)
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (`listed_in`)

---

# 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 🧹 Project Workflow

## 📌 Phase 1: Data Loading & Understanding
- Loaded CSV dataset
- Checked rows & columns
- Data types inspection
- Missing values analysis
- Duplicate detection

---

## 📌 Phase 2: Data Cleaning
- Converted `date_added` to datetime format
- Removed duplicate rows
- Cleaned string columns using `str.strip()`
- Handled missing values with `fillna()`

---

## 📌 Phase 3: Basic Analysis
- Counted Movies vs TV Shows
- Most common rating
- Top 10 countries
- Top genres
- Top directors

---

## 📌 Phase 4: Date & Trend Analysis
- Year with maximum Netflix additions
- Netflix growth over time
- Oldest and newest release year

---

## 📌 Phase 5: Duration Analysis
- Average movie duration
- Longest movie
- Shortest movie

---

## 📌 Phase 6: Filtering Tasks
- Indian movies after 2018
- TV-MA movies longer than 120 min
- Rajiv Chilaka content
- Salman Khan cast appearances

---

## 📌 Phase 7: GroupBy Analysis
- Content count by release year
- Rating-wise content count
- Country & type analysis

---

## 📌 Phase 8: Visualization
- Movies vs TV Shows bar chart
- Content trend line chart
- Top countries chart
- Top genres chart

---

## 📌 Phase 9: Advanced Analysis
- Most active content month
- Movies vs TV Shows over time
- India vs United States comparison
- Most frequent actors

---

# 📊 Key Insights & Findings

## 🔥 Major Findings:
- Movies dominate Netflix more than TV Shows
- TV-MA is one of the most common ratings
- United States and India are major content producers
- Netflix content growth accelerated significantly after 2015
- Drama and International Movies are highly common genres
- Certain actors and directors appear frequently across titles

---

# 📈 Visualizations Included
- Bar Charts
- Line Charts
- Trend Analysis
- Comparative Analysis

---

# 💼 Skills Demonstrated
- Data Cleaning
- Data Wrangling
- EDA
- Feature Transformation
- GroupBy Operations
- Data Visualization
- Real-world Dataset Analysis
- GitHub Project Structuring

---

# 📂 Project Files
```bash
Netflix-Data-Analysis/
│
├── netflix_titles.csv
├── netflix_analysis.ipynb
├── netflix_analysis.py
├── README.md
└── requirements.txt