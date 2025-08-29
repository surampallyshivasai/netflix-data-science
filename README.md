# 🎬 Netflix Data Analysis & Recommendation System

## 📌 Overview
This project explores the **Netflix Movies and TV Shows dataset** using **Exploratory Data Analysis (EDA)** and builds a simple **content-based recommendation system** using **TF-IDF Vectorization** on show descriptions.

It helps answer:
- What types of content (Movies vs TV Shows) dominate Netflix?
- Which countries produce the most content?
- How has Netflix's library grown over time?
- How can we recommend similar shows to users?

---

## 📂 Project Structure
netflix-ds/
│-- netflix_eda_recommender.ipynb # Main Jupyter Notebook
│-- netflix_titles.csv # Dataset
│-- requirements.txt # Dependencies
│-- README.md # Project documentation

yaml
Copy code

---

## 📊 Exploratory Data Analysis
- Distribution of **Movies vs TV Shows**
- **Top 10 countries** producing Netflix content
- Timeline of titles **added over the years**
- Data cleaning: handling missing values, duplicates, and formatting

---

## 🤖 Recommendation System
- Used **TF-IDF Vectorizer** on show descriptions  
- Computed **Cosine Similarity** to find similar titles  
- Example: Recommending shows similar to *Narcos*  

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/netflix-ds.git
   cd netflix-ds
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run Jupyter Notebook:

bash
Copy code
jupyter notebook
Open netflix_eda_recommender.ipynb to explore.

📸 Sample Visualizations
Movies vs TV Shows count

Content growth over time

Top contributing countries

(screenshots can be added here)

🌟 Insights
Netflix has more Movies than TV Shows.

US & India are top content producers.

Peak content addition happened around 2018–2020.

Content-based recommender suggests similar titles using descriptions.

🔮 Future Improvements
Add collaborative filtering (user-based recommendations)

Build a Streamlit dashboard for interactive use

Deploy as a web app

🙌 Credits
Dataset: [Netflix Titles on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download&SSORegistrationToken=CfDJ8BfigAjZUoJHuOjXpienVtDrMPutGbv2nAiTmQr9prPE5W6L-7nnfgXRf2zGhrj2ZH4NinB0AEGk16TUrpwjoO2kpBSbCHjcWfiaIIazCdb2TMMCp05jEjQenJnkpi16X0BkUNfHIlsJ9sxBrrWrJwVXs8SY3ux2D2zy80dmWAAtVgj7daMDYLuj41jd8JZqh0vtc6WoWu50njAWvsujXavxH76EYSjYT6waGCOiGwctX56Aa_GTJI9juhePx1b1dlA5017tICkYbRt4k4YtEdzasQ8uJhgONEKeNq0Rpup_a4bTGVfEgwtFhbicg17ph0Sybd6vfsBVqd0ppaZlWnxgNOA&DisplayName=Tech%20OnePlus8)

Developed by Shiva Sai Surampally
