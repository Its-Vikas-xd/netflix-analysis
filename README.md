# 🎬 Netflix Titles Data Analysis & Visualization

This project analyzes the [Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) using **Python**, **Pandas**, and **Matplotlib**. It produces visual insights into the distribution of movies vs TV shows, content ratings, durations, release years, and top contributing countries.

## 📁 Dataset

The dataset includes details about Netflix’s available content such as:

- `type`: Movie or TV Show  
- `title`, `director`, `cast`  
- `country`: Origin country  
- `release_year`: Release year  
- `rating`: Age classification  
- `duration`: Runtime or number of seasons  
- `description`: Content summary  

> Dataset file: `netflix_titles.csv`

---

## 📊 Visualizations Included

1. **Bar Chart** – Movies vs TV Shows
2. **Pie Chart** – Distribution of content ratings
3. **Histogram** – Duration distribution of movies
4. **Scatter Plot** – Release year vs number of titles
5. **Horizontal Bar Chart** – Top 10 countries by number of shows
6. **Line Charts** – Movies and TV shows released over the years

Each chart is saved as a PNG image in the working directory.

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- [Pandas](https://pandas.pydata.org/) – Data manipulation
- [Matplotlib](https://matplotlib.org/) – Visualization

---

## ▶️ How to Run

1. Clone the repo or download the `.py` file.
2. Make sure `netflix_titles.csv` is in the same directory.
3. Run the script:

```bash
python netflix_analysis.py
