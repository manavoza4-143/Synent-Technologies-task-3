# Synent-Technologies-task-3
# 📊 Exploratory Data Analysis (EDA) – Netflix Dataset



---

## 🧩 Problem Statement

With the rapid growth of streaming platforms like Netflix, understanding content trends, audience preferences, and performance metrics has become essential.
This project performs **Exploratory Data Analysis (EDA)** on a Netflix dataset to uncover **hidden patterns, trends, and relationships** in the data.

---

## 🎯 Objective

* Identify **trends and patterns** in Netflix content
* Perform **summary statistics analysis**
* Conduct **correlation analysis between features**
* Analyze **content trends over time**
* Generate **insights supported by visualizations**

---

## 📁 Dataset Details

* **Dataset Name:** netflix_movies_detailed_up_to_2025
* **Format:** CSV
* **Dataset Link:** netflix data set https://www.kaggle.com/datasets/bhargavchirumamilla/netflix-movies-and-tv-shows-till-2025

### 🔑 Key Features:

* `show_id` – Unique ID
* `type` – Movie / TV Show
* `title` – Content title
* `director`, `cast`, `country`
* `date_added` – Date added to platform
* `release_year` – Year of release
* `rating` – Content rating
* `duration` – Duration
* `genres`, `language`
* `popularity`, `vote_count`, `vote_average`
* `budget`, `revenue`

---

## ⚙️ Approach

### 1️⃣ Data Loading & Basic Pandas Operations

* Loaded dataset using **Pandas**
* Checked:

  * Dataset shape
  * Column names
  * Data types
  * Missing values
* Removed duplicates and handled null values

---

### 2️⃣ Summary Statistics

* Used `.describe()` for numerical insights
* Analyzed:

  * Mean
  * Median
  * Standard deviation
* Visualizations:

  * Histograms for distribution
  * Bar charts for categorical data

---

### 3️⃣ Feature Engineering

* Processed date columns
* Used `release_year` for trend analysis
* Cleaned and transformed relevant features

---

### 4️⃣ Correlation Analysis

* Selected numerical columns
* Generated **correlation matrix**
* Visualized using **heatmap** to identify relationships

---

### 5️⃣ Trend Identification

* Analyzed content trends using `release_year`
* Compared:

  * Movies vs TV Shows
* Used line plots and grouped visualizations

---

## 📊 Results & Insights

* 📈 **Content Growth:**
  Rapid increase in content production over recent years

* 🎬 **Content Type Distribution:**
  Movies dominate over TV Shows

* ⭐ **Ratings & Popularity:**
  Higher-rated content tends to have higher popularity

* 💰 **Budget vs Revenue:**
  Moderate relationship observed

* 🌍 **Global Distribution:**
  Content is concentrated in specific countries

---

## 📌 Conclusion

The EDA successfully identified key patterns and relationships within the Netflix dataset.
These insights can help in:

* Content strategy planning
* Recommendation systems
* Business decision-making

---

## 🚀 Future Scope

* Apply **Machine Learning models**
* Build **Recommendation System**
* Perform **Genre-based analysis**
* Use **advanced visualization tools (Seaborn / Plotly)**

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib

---

## 👨‍💻 Author

**Manav M Oza**

---
