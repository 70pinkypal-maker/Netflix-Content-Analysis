# 🎬 Netflix Content Analysis & ML Recommendation System

An end-to-end Data Analytics and Machine Learning project built using **Python, SQL, Machine Learning and Power BI** to analyze Netflix content and generate content-based recommendations.

---

## 📌 Project Overview

This project analyzes Netflix's content catalog to understand content distribution, ratings, genres, countries, content types and release-year trends.

Along with the analytics dashboard, a **content-based recommendation system** was developed using Machine Learning techniques to recommend titles similar to a selected Netflix title.

---

## 🎯 Project Objectives

- Analyze Netflix content distribution
- Compare Movies and TV Shows
- Analyze content by rating and genre
- Understand country-wise content distribution
- Analyze release-year trends
- Build an interactive Power BI dashboard
- Develop a content-based recommendation system
- Generate Top-N recommendations with similarity scores

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **TF-IDF**
- **Cosine Similarity**
- **Microsoft Power BI**
- **Data Visualization**

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of the Netflix catalog.

### Key KPIs

- Total Titles
- Total Directors
- Total Genres

### Key Visualizations

- Content by Rating
- Genres by Movies
- Movies vs TV Shows
- Content by Country
- Movies by Release Year
- Interactive Type and Title filters

---

## 📸 Dashboard Screenshots

### Netflix Content Analysis Dashboard

![Netflix Dashboard](Screenshots/dashboard.png)

### Netflix Recommendation System

![Netflix Recommendations](Screenshots/recommendations.png)

### ML Recommendation Output

![ML Recommendations](Screenshots/ml_recommendations.png)

## 🤖 Recommendation System

A **Content-Based Recommendation System** was developed using TF-IDF and Cosine Similarity.

### Recommendation Workflow

```text
Netflix Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Text Feature Combination
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Top-N Recommendations
      ↓
Power BI Dashboard
