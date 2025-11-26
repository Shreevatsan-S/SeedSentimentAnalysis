# SeedSentimentAnalysis

Sentiment analysis of edible-seed reviews collected from Indian e-commerce platforms — Pumpkin, Chia, Sunflower, Sesame, and Flax seeds.

---

## 📄 Overview

This project analyzes customer reviews from Amazon, Flipkart, BigBasket, and YouTube to understand sentiment trends related to edible seeds. After collecting and manually labeling reviews, NLP techniques, machine learning models, and visualization methods are applied to extract insights about product quality, customer satisfaction, and platform-wise sentiment differences.

---

## ⚙️ Key Features

- Aggregated review data from multiple Indian e-commerce platforms  
- Manual sentiment labeling using structured annotation criteria (Positive / Neutral / Negative)  
- Text preprocessing: cleaning, tokenization, stop-word removal  
- Exploratory Data Analysis (EDA) with visual insights  
- Sentiment classification using ML models (Logistic Regression, SVM, Random Forest, XGBoost)  
- Transformer-based NLP using BERT and DistilBERT  
- Dimensionality reduction and clustering (PCA, t-SNE, K-Means, Hierarchical Clustering)  
- Visualizations: word clouds, heatmaps, bar charts, bigram/trigram analysis  

---

## 📂 Repository Structure

```
/
├── DataSet/          # Raw and cleaned datasets
├── codes/            # Scripts for preprocessing, labeling, modeling, analysis
├── Plots/            # Visualizations (heatmaps, clusters, word clouds, etc.)
├── BI_plots/         # Business-focused dashboards and charts
└── README.md         # Project documentation
```

---

## 🧰 Technologies & Tools

- **Python**, **Jupyter Notebook**  
- **Pandas**, **NumPy**, **Scikit-learn**  
- **BERT / DistilBERT (HuggingFace)**  
- **Matplotlib**, **Seaborn**, **WordCloud**  
- **Tableau** (for BI dashboards)  
- **MySQL / MongoDB**  

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Shreevatsan-S/SeedSentimentAnalysis.git
cd SeedSentimentAnalysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run preprocessing

```bash
python codes/preprocess_reviews.py
```

### 4. Run analysis / sentiment model

```bash
python codes/run_analysis.py
```

### 5. View output visualizations

All plots are stored under:

```
Plots/
BI_plots/
```

---

## 📊 Example Outputs

- Sentiment distribution charts  
- Word clouds  
- Bigram & trigram visualizations  
- PCA and t-SNE scatter plots  
- Cluster dendrograms  
- Product-wise & platform-wise sentiment comparisons  

---

## 🎯 Business Applications

- Identify quality issues across seed types  
- Compare sentiment across platforms (Amazon, Flipkart, BigBasket)  
- Detect customer concerns regarding freshness, packaging, taste, quantity  
- Support product improvement and data-driven decision-making  
- Provide insights for marketing and inventory strategy  

---

## 📝 Future Enhancements

- Larger dataset with more platforms  
- Automated scraping pipeline  
- Aspect-based sentiment analysis (taste, freshness, packaging)  
- Streamlit / Power BI interactive dashboards  
- Multilingual review analysis  

---

## 📄 License

This project is under the **MIT License**.
