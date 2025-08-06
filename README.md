# 🎬 IMDB Movie Data Analysis 

A comprehensive **Exploratory Data Analysis (EDA)** project using **IMDB movie data** to uncover industry insights and visual patterns. This project uses Python libraries like **pandas**, **numpy**, **matplotlib**, and **seaborn** to explore trends in **ratings, budgets, genres, gross revenue**, and more.

---

## 🎯 Project Objective

To clean and explore a real-world IMDB dataset to answer questions such as:

- Which genres are the most popular and profitable?  
- How do ratings relate to gross earnings?  
- Are longer movies better rated or more successful?  
- What are the trends in movie releases over the years?

> This analysis provides a data-driven perspective of the movie industry.

---

## 🎞️ Dataset Overview

| Column            | Description                            |
|-------------------|----------------------------------------|
| `title`           | Movie title                            |
| `genre`           | Primary genre                          |
| `duration`        | Duration (minutes)                     |
| `budget`          | Budget in USD                          |
| `gross`           | Worldwide gross revenue in USD         |
| `rating`          | IMDB rating (0–10)                     |
| `votes`           | Number of user votes                   |
| `year`            | Release year                           |

> Dataset Source: [Kaggle - IMDB Dataset](https://www.kaggle.com/)

---

## 🧹 Data Cleaning Steps

- Removed duplicates and missing values  
- Handled incorrect data types (e.g., budget, gross)  
- Converted categorical features for analysis  
- Normalized outliers in numerical columns

---

## 📊 Exploratory Visualizations

| Visualization                  | Insight Example                                            |
|--------------------------------|------------------------------------------------------------|
| Genre Distribution             | Drama & Action dominate, followed by Comedy               |
| Rating vs. Gross Revenue       | Slight positive correlation — not always linear           |
| Budget vs. Gross               | Higher budget often results in higher gross, but not always |
| Yearly Movie Count             | Significant increase post-2000                            |
| Top Rated vs. Top Grossing     | Popularity ≠ Profitability                                |

> 📂 All plots are saved in `/visuals/` directory.

---

## 🧰 Tools & Libraries

- Python 🐍  
- pandas 🧾  
- numpy 🔢  
- matplotlib 📉  
- seaborn 🎨  
- Jupyter Notebook 📓

---



