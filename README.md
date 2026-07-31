# Amazon-Prime-Content-Analytics-Using-EDA-Machine-Learning-
**Amazon Prime Content Analytics Using EDA &amp; Machine Learning** analyzes Amazon Prime Movies and TV Shows to uncover content trends and insights. The project includes data cleaning, EDA, and machine learning to identify patterns, segment similar content, and generate data-driven insights for better content analysis and decision-making.
# 📊 Amazon Prime Content Analytics Using EDA & Machine Learning

## 📌 Project Overview

Amazon Prime has one of the world's largest digital streaming libraries, offering thousands of movies and TV shows across multiple genres, languages, and countries. Understanding this massive collection is essential for identifying audience preferences, improving content recommendations, and supporting strategic business decisions.

This project performs an end-to-end analysis of Amazon Prime's content library using **Exploratory Data Analysis (EDA)** and **Machine Learning**. The objective is to transform raw streaming data into meaningful business insights by analyzing content distribution, release trends, genres, ratings, popularity, runtime, production countries, and audience engagement. The project demonstrates the complete data analytics workflow, from data preprocessing to visualization, pattern discovery, and business interpretation. It is based on two datasets—**titles.csv** and **credits.csv**—which together provide detailed information about movies, TV shows, actors, directors, ratings, and production details.

---

# 🎯 Problem Statement

The rapid growth of online streaming platforms has created an enormous collection of entertainment content, making it difficult to understand viewing patterns and content performance. Amazon Prime requires a data-driven approach to identify popular genres, analyze rating trends, evaluate content growth over time, and understand the characteristics of successful movies and TV shows.

This project aims to solve these challenges by exploring the Amazon Prime dataset, discovering hidden trends, and generating insights that can improve content acquisition, recommendation systems, audience engagement, and overall business strategy.

---

# 📂 Dataset Information

The analysis is performed using two publicly available datasets.

### **titles.csv**

Contains detailed information about every movie and TV show, including:

* Title
* Content Type
* Release Year
* Genres
* Runtime
* IMDb Rating
* TMDB Score
* TMDB Popularity
* Production Countries
* Age Certification

### **credits.csv**

Contains cast and crew information such as:

* Actor Name
* Director Name
* Character
* Role
* Content ID

Both datasets are connected using the common **id** column, allowing content information to be combined with cast and crew details for deeper analysis.

---

# ⚙️ Project Workflow

The project follows a structured data analytics pipeline to convert raw streaming data into actionable business insights.

### 1. Data Collection

The Amazon Prime Movies and TV Shows datasets were imported into Python and loaded into Pandas DataFrames for analysis. Initial exploration included checking dataset dimensions, column information, data types, descriptive statistics, and overall dataset quality.

### 2. Data Cleaning & Preprocessing

Before analysis, the datasets were cleaned to ensure consistency and reliability. Duplicate records were removed, missing values were handled using appropriate statistical techniques, incorrect data types were corrected, and categorical variables were standardized. Finally, both datasets were merged using the common **id** column to create a unified dataset for analysis.

### 3. Exploratory Data Analysis (EDA)

After preprocessing, extensive exploratory data analysis was performed to understand the characteristics of Amazon Prime's content library. Multiple visualizations were created to analyze content distribution, yearly growth, genre popularity, ratings, runtime, production countries, age certifications, and audience engagement. Relationships between numerical variables such as IMDb ratings and TMDB popularity were also examined to identify meaningful patterns.

### 4. Machine Learning

Beyond visualization, machine learning techniques were applied to discover hidden structures within the dataset. Similar titles were grouped based on their characteristics, enabling content segmentation and supporting a deeper understanding of the streaming catalog. These patterns can help improve recommendation systems and guide future content acquisition decisions.

---

# 🔍 Exploratory Data Analysis

The EDA phase focused on answering key business questions related to Amazon Prime's content library. More than twenty meaningful visualizations were developed to explore different aspects of the dataset.

The analysis included:

* Distribution of Movies vs TV Shows
* Content growth over time
* Most popular genres
* Runtime distribution
* IMDb rating analysis
* TMDB popularity trends
* Age certification analysis
* Production country distribution
* Actor and director participation
* Relationship between ratings and popularity
* Audience engagement patterns

Each visualization was interpreted from a business perspective, helping transform raw data into actionable insights that support strategic decision-making.

---

# 🎯 Objectives

* Analyze Amazon Prime's streaming content library.
* Identify trends in movies and TV shows over time.
* Explore genre popularity and audience preferences.
* Evaluate IMDb ratings and TMDB popularity.
* Discover relationships between content characteristics.
* Apply machine learning to identify similar content groups.
* Generate actionable business insights for content strategy and recommendation systems.
# 📈 Key Insights

The analysis uncovered several meaningful insights about Amazon Prime's streaming library. Movies make up a significantly larger share of the platform than TV Shows, indicating a stronger focus on film content. The number of titles released has increased rapidly over the last two decades, reflecting continuous investment in expanding the platform's catalog. Drama, Comedy, Action, and Documentary emerged as the most popular genres, highlighting strong audience demand for these categories.

IMDb ratings revealed that most titles score between **6 and 8**, suggesting that the majority of Amazon Prime's content is well-received by viewers. Runtime analysis showed that most movies fall within **80–120 minutes**, which aligns with typical viewer preferences. The United States contributes the highest number of titles, while several other countries also play important roles in content production. Relationships between IMDb ratings and TMDB popularity indicate that higher-rated content generally attracts greater audience attention and engagement. These insights provide valuable guidance for future content acquisition, production planning, and recommendation strategies.

---

# 🤖 Machine Learning Approach

After completing the exploratory data analysis, machine learning techniques were applied to discover hidden patterns within the dataset. Content features such as ratings, runtime, release year, genres, and popularity were prepared through preprocessing and feature engineering before model development.

The machine learning model grouped similar movies and TV shows into meaningful clusters based on their characteristics. This segmentation helps identify content with similar audience appeal and supports personalized recommendations. By analyzing these clusters, streaming platforms can better understand content diversity, improve recommendation systems, and make informed decisions about future content investments.

---

# 📊 Business Impact

The insights generated from this project can help streaming platforms make data-driven business decisions by:

* Understanding audience preferences across different genres.
* Identifying high-performing content categories.
* Improving personalized recommendation systems.
* Supporting strategic content acquisition.
* Optimizing investments in movies and TV shows.
* Expanding content into emerging international markets.
* Enhancing customer engagement and retention.

---

# 🛠 Repository Structure

```text
Amazon-Prime-Content-Analytics/
│
├── Dataset/
│   ├── titles.csv
│   ├── credits.csv
│
├── Notebook/
│   └── Amazon_Prime_Content_Analytics.ipynb
│
├── Images/
│   ├── Movies_vs_TVShows.png
│   ├── Genre_Distribution.png
│   ├── IMDb_Ratings.png
│   ├── Runtime_Distribution.png
│   └── Content_Growth.png
│
├── README.md
└── requirements.txt
```

---

# 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/Amazon-Prime-Content-Analytics.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
jupyter notebook
```

Open the notebook and execute all cells to reproduce the complete analysis.

---

# 📌 Results

This project successfully demonstrates an end-to-end data analytics workflow using a real-world streaming dataset. Beginning with raw data collection and preprocessing, the project progresses through exploratory data analysis, visualization, and machine learning to generate meaningful business insights. The findings reveal important trends in content growth, genre popularity, ratings, production countries, and audience preferences. These insights can assist streaming platforms in optimizing their content strategy, improving recommendation systems, and delivering a better viewing experience for users.


# 🔮 Future Enhancements

* Build an AI-powered movie recommendation system.
* Develop an interactive Power BI dashboard.
* Perform sentiment analysis using user reviews.
* Predict IMDb ratings using supervised machine learning models.
* Deploy the project as an interactive web application.
* Integrate real-time streaming data for continuous analysis.


# 💡 Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Statistical Analysis
* Machine Learning
* Business Intelligence
* Data Storytelling
* Insight Generation
* Problem Solving


# 📚 Conclusion

This project showcases the complete lifecycle of a real-world data analytics solution—from raw data preparation to business insight generation. By combining Exploratory Data Analysis with Machine Learning, it uncovers valuable patterns in Amazon Prime's content library and demonstrates how data can drive smarter business decisions. The project reflects practical expertise in Python-based analytics, visualization, feature engineering, and business interpretation, making it a strong portfolio project for Data Analyst, Business Analyst, and Machine Learning roles.



