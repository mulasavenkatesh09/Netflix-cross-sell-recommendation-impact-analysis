# Netflix Cross-Sell & Recommendation Impact Analysis

<p align="center">
<img src="https://user-images.githubusercontent.com/96771321/214456292-ef421cff-a59f-46a1-9411-fef980ee6814.gif" width="400">
</p>

---

## 📌 Project Overview

Modern streaming platforms such as Netflix and Amazon rely heavily on recommendation systems to increase user engagement and improve content discovery. Beyond recommending similar items, organizations evaluate how recommendations influence user behavior, viewing decisions, and overall platform value.

This project develops a **content-based recommendation system** and extends it into a **recommendation impact analysis framework** to evaluate cross-content relationships and personalization effectiveness using Netflix content data.

In addition to recommendation modeling, **interactive Tableau dashboards** were developed to analyze global content distribution, ratings patterns, and catalog growth trends, enabling business-level insights similar to real streaming analytics environments.

The goal is to simulate how recommendation engines contribute to increased engagement and cross-content consumption.

---

## 🧠 Business Problem

Streaming platforms aim to increase user engagement and viewing diversity. Without effective recommendations:

- Users struggle to discover relevant content  
- Engagement time decreases  
- Cross-content consumption remains low  

Recommendation systems help platforms guide users toward relevant content while improving overall platform performance.

---

## 🎯 Project Objectives

- Build a content-based recommendation engine using Netflix metadata  
- Analyze relationships between similar content categories  
- Evaluate recommendation-driven cross-content discovery  
- Measure personalization impact through similarity modeling  
- Simulate recommendation uplift and engagement improvement  
- Visualize catalog insights and engagement trends using Tableau dashboards  

---

## 📊 Dataset

The project uses the Netflix Movies and TV Shows dataset containing metadata such as:

- Director  
- Cast  
- Country  
- Genres  
- Content Type  
- Release Year  
- Ratings and Duration  

Dataset Source:  
https://www.kaggle.com/datasets/shivamb/netflix-shows

---

## ⚙️ Recommendation Approach

The recommendation engine is based on **content similarity analysis**.

### Key Features Used

- Director  
- Cast  
- Country  
- Genres  
- Type (Movie / TV Show)

### Methodology

1. Data Collection and Cleaning  
2. Feature Engineering and Text Vectorization  
3. Similarity Matrix Construction  
4. Content-Based Recommendation Generation  
5. Recommendation Impact Analysis  
6. Business Insight Visualization using Tableau  

Cosine similarity is used to measure closeness between titles and generate recommendations.

---

## 🔍 Cross-Sell & Recommendation Analysis

Instead of only generating recommendations, this project evaluates how recommendations influence content discovery.

Analysis includes:

- Similar genre consumption patterns  
- Content relationship discovery  
- Recommendation similarity scoring  
- Cross-content viewing opportunities  

This simulates cross-sell strategies commonly used in digital marketplaces and streaming platforms.

---

## 📊 Tableau Dashboard Analytics

Interactive dashboards were created in **Tableau** to translate recommendation insights and dataset exploration into business-focused visual analytics.

### Dashboard Highlights

#### 🌍 Global Content Distribution
- Map visualization showing total Movies & TV Shows by country.
- Identifies regional content production concentration and geographic catalog diversity.

#### ⭐ Ratings Analysis
- Distribution of maturity ratings across titles.
- Helps understand audience segmentation and content targeting strategy.

#### 🎬 Movies vs TV Shows Distribution
- Catalog composition visualization comparing Movies and TV Shows.
- Reveals platform investment balance between long-form series and movies.

#### 🎭 Top Genres Analysis
- Identifies dominant genres contributing to catalog diversity.
- Supports content acquisition and recommendation strategy insights.

#### 📈 Content Growth Trend
- Year-wise expansion of Netflix catalog.
- Shows rapid platform growth after 2016 aligned with global streaming adoption.

These dashboards simulate executive-level analytics reporting used by product, content strategy, and growth teams.

---

## 📈 Simulated Business Impact

- Increased content discovery efficiency  
- Improved cross-content recommendation relevance  
- Enhanced personalization capability  
- Better strategic understanding of catalog composition  
- Higher engagement potential through related content suggestions  

---

## 🌐 Application Interface

An interactive interface was developed using **Streamlit** to allow users to:

- Search for a movie or TV show  
- Receive similar content recommendations  
- Explore recommendation relationships visually  

Run locally:

```bash
streamlit run app.py
```

---

## 🛠️ Technologies Used

- Python  
- Pandas & NumPy  
- Scikit-learn  
- NLP Feature Vectorization  
- Cosine Similarity  
- Streamlit  
- Tableau (Interactive Analytics Dashboards)

---

## 📈 Outcome

The project demonstrates how recommendation systems can be evaluated not only for algorithmic accuracy but also for their business impact in improving content discovery and engagement.

By combining **machine learning recommendations with Tableau business dashboards**, the project reflects real-world analytics workflows used by streaming platforms to support product, content, and strategy decisions.

---

## 🔮 Future Improvements

- User behavior–based collaborative filtering  
- A/B testing simulation for recommendation impact  
- Lift and recommendation conversion analysis  
- Hybrid recommendation system implementation  
- Advanced engagement analytics dashboards  

---

## 🙌 Acknowledgement

This project is inspired by modern recommendation system design and personalization analytics practices used in large-scale digital platforms.
