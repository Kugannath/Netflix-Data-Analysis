# 🎬 Netflix Data Analysis

## 📄 Overview
This project analyzes the Netflix Movies and TV Shows dataset to uncover insights into content trends, genres, countries, and release patterns.  
The goal is to perform **data cleaning, exploratory analysis, and visualization** using Python.

## 🧰 Tools & Libraries Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## 📊 Dataset
**Source:** [Netflix Movies and TV Shows - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
**Rows:** ~8,800  
**Columns:** 12 (includes `title`, `type`, `country`, `release_year`, `rating`, etc.)

## ⚙️ Workflow
1. **Data Loading & Cleaning**
   - Removed duplicates and handled missing values
   - Converted date formats and extracted `year_added`
2. **Exploratory Data Analysis (EDA)**
   - Movies vs TV Shows distribution  
   - Top countries producing content  
   - Content addition over years  
   - Top genres and directors  
   - Rating distribution  

## 📈 Visual Insights
- Netflix has a larger proportion of **Movies** than TV Shows.  
- Content addition has grown sharply after **2015**.  
- **United States** and **India** lead in total titles produced.  
- Popular genres include **Dramas, Comedies, and International Movies**.  

## 🧠 Key Takeaways
- Netflix has diversified content globally since 2015.  
- A majority of its catalog is targeted toward **mature audiences (TV-MA, TV-14)**.  
- Data-driven content strategy is evident through increased regional variety.

## 📂 Project Structure
Netflix-Data-Analysis/
│
├── Netflix_Analysis.ipynb # Main notebook
├── README.md # Project summary
├── datasets/
│ └── netflix_titles.csv
└── visuals/
├── genre_plot.png
├── rating_plot.png
└── country_plot.png

## 👩‍💻 Author
**Kugannath**  
Data Enthusiast | Python & SQL Learner | Aspiring Data Analyst  
