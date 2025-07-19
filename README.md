# 📊 Social Media Trend Analysis

Analyze viral trends across major social media platforms using Python. This project focuses on identifying popular platforms, trending hashtags, high-engagement regions, and predicting the most suitable platform based on user interaction metrics.

---

## 📁 Project Overview

In this project, we analyzed a dataset of viral social media content to:
- Explore engagement metrics (views, likes, shares, comments)
- Visualize top-performing platforms, hashtags, and regions
- Create a machine learning model to classify the most suitable platform for content

---

## 🔧 Tools & Technologies

- **Python**
- **Pandas** and **NumPy** – Data manipulation
- **Matplotlib** and **Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning (Classification)
- **Jupyter Notebook**

---

## 🔍 Exploratory Data Analysis (EDA)

- **Post Count by Platform** – Bar chart visualization
- **Top Hashtags** – Horizontal bar plot
- **Top 5 Regions** – Pie chart
- **Boxplot** – Distribution of Views, Likes, Shares, and Comments (with outliers)
- **Heatmap** – Correlation between engagement metrics

---

## 🛠️ Feature Engineering

- Created a new feature: `Engagement` = Likes + Shares + Comments
- Converted `Views` into scaled format using `MinMaxScaler`
- Encoded categorical column `Platform` into numerical labels for ML

---

## 🤖 Machine Learning Model

- **Objective**: Predict the most suitable platform for a post based on its metrics
- **Model**: Logistic Regression Classifier
- **Accuracy**: ~84% on test data
- **Target Variable**: `Platform`

---

## 📈 Results & Insights

- YouTube and Instagram dominate high-engagement content
- Hashtags with emotional or trendy terms perform better
- The model can help marketers decide the best platform to launch new content

---

## ✅ Conclusion

This project demonstrates how data from social media can be turned into insights using EDA and ML. It offers a basic predictive model and can be extended with NLP, time-series, or sentiment analysis for deeper trends.

---

## 📂 Project Structure

