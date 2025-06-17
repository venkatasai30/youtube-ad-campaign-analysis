# 📘 YouTube Ad Campaign Analysis – Project Requirements Document

## 🔍 Project Title:
**Understanding YouTube Video Popularity and Categorization for Targeted Advertising**

---

## 🧠 Project Overview:
A client is planning to run an online advertising campaign on YouTube. Before investing money, they want to gain insights into how YouTube videos perform, what factors influence their popularity, and how to categorize videos based on comments and metadata. The ultimate goal is to identify high-performing video categories for ad targeting.

---

## 🎯 Business Objectives:

1. Identify the key factors that affect a YouTube video’s popularity.
2. Categorize or cluster YouTube videos based on comments and statistics.
3. Recommend optimal content types (categories, formats) for ad placement.
4. Enable the client to make data-driven decisions before launching ad campaigns.

---

## 📌 Functional Requirements:

### 1. Data Collection
- Collect YouTube data using data resources.
- Required fields:
  - Video ID, Title, Description
  - Category ID, Tags
  - Views, Likes, Dislikes, Comments Count
  - Published Date, Duration
  - Top comments with text and metadata

### 2. Data Preprocessing
- Clean and transform:
  - Normalize statistics (e.g., views per day)
  - Convert duration and timestamps
  - Clean comments (remove emojis, stop words, etc.)
  - Handle missing data and outliers.

### 3. Video Categorization
- Use Natural Language Processing (NLP) to analyze video comments and titles.
- Techniques:
  - Sentiment analysis
  - Topic modeling (e.g., LDA)
  - Text classification (TF-IDF + ML model or BERT)
- Output:
  - Assign each video a meaningful label (e.g., "Educational", "Entertainment", "Product Review").

### 4. Popularity Analysis
- Identify which features impact popularity (views, likes, shares).
- Analyze:
  - Video metadata (title length, tags)
  - Category-wise performance
  - Comment sentiment vs. video popularity
- Build regression or classification models to predict popularity (e.g., high/medium/low engagement).

### 5. Visualization & Reporting
- Create visual dashboards using Power BI, Tableau, or Python (Plotly/Seaborn).
- Show:
  - Most popular video categories
  - Engagement trends by category or channel
  - Sentiment analysis results
  - Recommendations for targeting

---

## 🔧 Technical Stack

| Area              | Tools/Technologies                  |
|-------------------|-------------------------------------|
| Data Collection   | Python, YouTube Data API v3         |
| Data Processing   | Pandas, NumPy                       |
| NLP               | NLTK, spaCy, BERT, Transformers     |
| ML Modeling       | Scikit-learn, XGBoost               |
| Visualization     | Power BI, Tableau, Plotly, Seaborn  |
| Deployment (opt.) | Streamlit, Flask                    |

---

## 📊 Deliverables

- Cleaned dataset and code notebooks
- Categorized video list with sentiment scores
- Popularity prediction model
- Final report or dashboard for insights
- (Optional) Web app to demo insights

---

## 📅 Timeline (Suggested)

| Week | Milestone                            |
|------|--------------------------------------|
| 1    | Data collection, API integration     |
| 2    | Data cleaning and transformation     |
| 3    | NLP & video categorization           |
| 4    | Popularity prediction model          |
| 5    | Dashboard/reporting & final review   |

---

## ✅ Success Criteria

- Accurate video categorization using NLP
- Reliable prediction of video popularity
- Clear business insights for ad targeting
