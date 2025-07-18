# 📊 Netflix Data Analysis Project

![Netflix Banner](https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg)

## 📁 Project Overview

This project performs an exploratory data analysis (EDA) on Netflix’s dataset using Python. The analysis uncovers insights about Netflix's content distribution, genre trends, production years, and other key metrics. It aims to help stakeholders understand viewing trends, content diversity, and Netflix’s strategic direction.

---

## 🧠 Objective

- Analyze Netflix's dataset to discover patterns in content distribution by type, country, year, and genre.
- Clean and preprocess the data for reliable visualizations.
- Generate insights to assist in content planning and business strategy.

---

## 📂 Dataset

- **Source:** [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
- **Format:** CSV
- **Features:**
  - `show_id`
  - `type` (Movie or TV Show)
  - `title`
  - `director`
  - `cast`
  - `country`
  - `date_added`
  - `release_year`
  - `rating`
  - `duration`
  - `listed_in` (Genres)
  - `description`

---

## 🛠️ Tools & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

---

## 📌 Key Steps

### 1. Data Cleaning
- Removed duplicates and null values.
- Standardized column formats (`date_added`, `duration`, etc.)

### 2. Feature Engineering
- Extracted year from `date_added`.
- Split duration into numerical and categorical parts.

### 3. Exploratory Data Analysis (EDA)
- Most common genres and countries.
- Trend of content added per year.
- Ratings distribution and content duration analysis.


## 📈 Insights & Findings

- Movies make up the majority of Netflix content.
- USA, India, and UK are the leading content-producing countries.
- The peak year of content addition was around 2019–2020.
- TV Shows are typically shorter in duration but growing in popularity.
- Certain directors and actors appear frequently in Netflix's catalog.

---

## 🚀 Future Work

- Sentiment analysis on descriptions.
- Content recommendation engine based on genres and cast.
- Time series forecasting for future content trends.

---

## 💡 Conclusion

This project demonstrates the power of data analytics in understanding content strategy for OTT platforms like Netflix. It can help producers, marketers, and business analysts make informed decisions based on real-world data.

---

## 📎 How to Run

1. Clone this repo or download the notebook.
2. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud
   ```
3. Run the notebook in Jupyter or any Python IDE.

---

## 🤝 Contribution

Feel free to fork the repository and submit pull requests. All contributions are welcome!

---

## 🧾 License

This project is licensed under the MIT License.
