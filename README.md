# 🎬 Netflix Data Analysis Project

---

## **__📌 Project Overview__**
This project performs an **Exploratory Data Analysis (EDA)** on the *Netflix Movies and TV Shows* dataset to uncover trends related to content type, release patterns, duration, countries, and genres.

The goal is to **analyze Netflix’s content strategy** using Python and present meaningful insights in a clear and visual way.

---

## **__📂 Dataset Information__**
- **Dataset Name:** Netflix Movies and TV Shows  
- **Source:** Kaggle  
- **File:** `netflix_titles.csv`  
- **Records:** ~8,800  
- **Features:** 12 columns (title, type, country, rating, duration, etc.)

---

## **__🛠️ Tools & Technologies Used__**
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## **__🔍 Data Cleaning Steps__**
The following preprocessing steps were applied:

- Handled missing values in **director, cast, and country**
- Converted `date_added` to datetime format
- Extracted numerical values from `duration`
- Created new columns such as:
  - `year_added`
  - `duration_num`
  - `is_movie`

These steps improved data consistency and usability for analysis.

---

## **__📊 Exploratory Data Analysis (EDA)__**

### ✔ Movies vs TV Shows Distribution
- Compared the total number of Movies and TV Shows available on Netflix.

### ✔ Content Added Over the Years
- Analyzed how Netflix content has grown year-by-year.

### ✔ Country-wise Content Production
- Identified top countries contributing to Netflix’s catalog.

### ✔ Genre Analysis
- Found the most common genres available on Netflix.

### ✔ Duration Analysis
- Studied movie durations and TV show seasons.

---

## **__📈 Key Insights__**
- 🎥 Movies dominate the Netflix catalog, but TV Shows have grown rapidly after 2018  
- 🌍 United States and India are the top content-producing countries  
- ⏱️ Most movies fall within the **80–120 minutes** range  
- 🎭 Drama and Comedy are the most frequent genres  
- 📅 Netflix content addition peaked between **2018–2020**

---

