# 🎬 Netflix Dataset Analysis Project

**Author:** Darshil Halvadia  
**Type:** Major Project – Data Analytics  

---

## 🔹 Overview

This project analyzes Netflix’s content dataset to uncover insights about movies, TV shows, genres, countries, ratings, and content trends over the years. The goal is to provide a **data-driven understanding of Netflix’s content library** and visualize key patterns for strategic decisions.

The project is implemented in **Python**, using **Pandas, NumPy, Matplotlib, and Seaborn**. It can be run as a Python script or in a Jupyter Notebook for interactive analysis.

---

## 🔹 Key Features

- **Dataset Cleaning & Preparation**  
  - Handles missing values in `director`, `cast`, `country`, `rating`, and `listed_in` columns  
  - Converts date columns and extracts `year_added`  
  - Standardizes column names  

- **Content Type Analysis**  
  - Pie chart showing **Movies vs TV Shows**  
  - Clear insights about Netflix’s content focus  

- **Content Growth Analysis**  
  - Year-wise content addition plot  
  - Highlights Netflix’s global expansion and growth trends  

- **Genre Analysis**  
  - Top 10 genres displayed with bar charts  
  - Explodes multiple genres for accurate count  

- **Country Analysis**  
  - Top 10 countries producing Netflix content  
  - Insights into global reach  

- **Ratings Analysis**  
  - Distribution of ratings (`TV-MA`, `TV-14`, etc.)  
  - Ratings comparison by content type (Movies vs TV Shows)  

- **Movie Duration Analysis**  
  - Histogram with **KDE curve** for movie durations  
  - Average duration calculation  

- **Country vs Genre Heatmap**  
  - Cross-tab heatmap for top countries and top genres  

- **Final Insights Summary**  
  - Key findings summarized for business strategy  

---

## 🔹 Libraries Used

- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Basic plotting  
- **Seaborn** – Advanced visualization  

---

## 🔹 Dataset

The dataset used is `Netflix Dataset.csv`. Please ensure it is present in the same folder as the script/notebook.  
> You can replace it with your own dataset following the same column structure.

---

## 🔹 Usage

1. Clone the repository:  
```bash
git clone <repository_url>


Requirment Libaray
pip install pandas numpy matplotlib seaborn
