# 📸 Top Instagram Influencers Data Analysis

This project dives deep into the world of top Instagram influencers, analyzing their reach, engagement, and influence using real-world data. We apply data cleaning, feature engineering, exploratory analysis, and machine learning to predict an influencer's **Influence Score** and extract actionable **business insights**.

---

## 📁 Dataset Overview

The dataset includes 200 top Instagram influencers with attributes like:

- `rank`: Ranking by followers
- `channel_info`: Instagram username
- `influence_score`: Calculated metric based on visibility & engagement
- `followers`, `posts`, `avg_likes`, `total_likes`
- `60_day_eng_rate`: Recent engagement rate
- `new_post_avg_like`: Avg likes on recent posts
- `country`: Origin country

---

## 🔧 Project Workflow

### 1. **Data Cleaning & Preprocessing**
- Converted shorthand symbols (K/M/B/%) to numeric
- Filled missing values
- Standardized data types

### 2. **EDA (Exploratory Data Analysis)**
- Visualized followers vs. engagement
- Distribution of influence scores
- Top countries by influencer count

### 3. **Feature Engineering**
- Created new metrics:
  - `like_follower_ratio`
  - `post_follower_ratio`
  - `avg_likes_ratio`

### 4. **Modeling**
- Trained a `RandomForestRegressor` to predict **Influence Score**
- Evaluated using R² Score and Mean Squared Error (MSE)

### 5. **Interpretation**
- Feature importance analysis to uncover top predictors

### 6. **Prediction Visualization**
- Plotted predicted vs actual scores to verify performance

### 7. **Business Insights**
- Identified:
  - High engagement micro-influencers
  - Influencers with growing traction
  - Country-level strategic markets

---

## 🤖 Technologies Used

- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook
- Machine Learning: Random Forest Regressor
- Data Visualization

---

## 📈 Key Insights

- **Followers alone don’t define influence** — engagement metrics and ratios matter more.
- **Micro-influencers** with strong engagement offer great value.
- Emerging influencers can be identified by comparing **new vs avg likes**.
- Top influencer countries include the USA, India, and Brazil.

---

## 🚀 Future Improvements

- Add classification model to label engagement level (Low/Med/High)
- Build a Streamlit dashboard for business use
- Deploy the model as an API using Flask

---

## 📂 Project File

The entire analysis is in the Jupyter Notebook:  
📄 `Top Instagram Influencers Data Analysis.ipynb`

---


