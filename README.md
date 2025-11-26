# SeedSentimentAnalysis

Sentiment analysis of edible-seed reviews collected from Indian e-commerce platforms — Pumpkin, Chia, Sunflower, Sesame, and Flax seeds.

---

## 📄 Overview

This project analyzes customer reviews from Amazon, Flipkart, BigBasket, and YouTube to understand sentiment trends related to edible seeds. After collecting and manually labeling reviews, we apply NLP techniques, machine learning models, and visualization methods to extract insights about product quality, customer satisfaction, and platform-wise sentiment differences.

---

## ⚙️ Key Features

- Aggregated review data from multiple Indian e-commerce platforms  
- Manual sentiment labeling using strict annotation criteria (Positive / Neutral / Negative)  
- Text preprocessing: cleaning, tokenization, stop-word removal  
- Exploratory Data Analysis (EDA) to identify patterns and anomalies  
- Sentiment classification using ML models (Logistic Regression, SVM, Random Forest, XGBoost)  
- Advanced NLP using transformer models (BERT, DistilBERT)  
- Dimensionality reduction and clustering (PCA, t-SNE, K-Means, Hierarchical)  
- Visualizations including word clouds, heatmaps, bar charts, bigrams/trigrams  
- Business-intelligence focused insights on product performance and customer pain points  

---

## 📂 Repository Structure

```plaintext
/
├── DataSet/          # Raw and cleaned datasets
├── codes/            # Scripts for preprocessing, labeling, modeling, and analysis
├── Plots/            # Analytical visualizations (EDA, clusters, heatmaps, etc.)
├── BI_plots/         # Business-intelligence dashboards and summarized charts
└── README.md         # Project documentation
