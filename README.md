# 🎬 Netflix Movies Exploratory Data Analysis (Python)

This project performs exploratory data analysis (EDA) on a Netflix movies dataset to uncover trends in genres, popularity, ratings, and release patterns. The goal is to understand content distribution and audience engagement using Python-based data analysis and visualization.

---

## 📌 Problem Statement

Streaming platforms like Netflix rely heavily on data to decide:
- What type of content to invest in  
- Which genres perform best  
- How audience engagement varies across movies  
- How content production trends change over time  

This project analyzes Netflix movie data to answer such questions using structured EDA techniques.

---

## 📂 Dataset

- Source: Movie metadata dataset (Netflix catalog)
- Rows: ~9,800 movies  
- Key Columns:
  - `Title`
  - `Release_Date`
  - `Genre`
  - `Popularity`
  - `Vote_Count`
  - `Vote_Average`
  - `Original_Language`

---

## 🔍 Questions Answered

1. What are the most frequent movie genres on Netflix?  
2. Which movies have the highest average ratings?  
3. Which movies are the most popular and what genres do they belong to?  
4. Which movies have the lowest popularity scores?  
5. Which year saw the highest number of movie releases on Netflix?

---

## 📊 Key Insights

- 🎭 **Drama and Comedy dominate** the Netflix catalog, indicating strong focus on mass-appeal genres.  
- 🌟 **Popularity is heavily skewed** toward blockbuster franchises and mainstream titles.  
- 📅 **2021 saw the highest number of releases**, reflecting post-pandemic content expansion.  
- 📉 Movies with extremely high ratings but very low vote counts can be misleading — filtering by vote count is important for reliable ranking.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📈 Visualizations Included

- Top 10 most frequent genres  
- Top 10 highest-rated movies  
- Top 5 most popular movies  
- Top 5 least popular movies  
- Top 5 years with the most movie releases  

All visualizations are saved as high-resolution PNGs for documentation.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt

