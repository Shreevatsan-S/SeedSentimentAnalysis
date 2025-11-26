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

/ (root)
|-- DataSet/ # Raw and cleaned datasets
|-- codes/ # Scripts for preprocessing, labeling, modeling, and analysis
|-- Plots/ # Analytical visualizations (EDA, clusters, heatmaps, etc.)
|-- BI_plots/ # Business-intelligence dashboards and summarized charts
|-- README.md # Project documentation

yaml
Copy code

---

## 🧰 Technologies & Tools

- **Python**  
- **Pandas, NumPy, Scikit-learn**  
- **BERT, DistilBERT (HuggingFace)**  
- **Matplotlib, Seaborn, WordCloud**  
- **Tableau (for dashboards)**  
- **Jupyter Notebook**  
- **MySQL / MongoDB**  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/Shreevatsan-S/SeedSentimentAnalysis.git
cd SeedSentimentAnalysis
2. Install dependencies
bash
Copy code
pip install -r requirements.txt
3. Run preprocessing (edit script name if needed)
bash
Copy code
python codes/preprocess_reviews.py
4. Run analysis / training
bash
Copy code
python codes/run_analysis.py
5. View results
All visualizations are stored in:

Copy code
Plots/
BI_plots/
📊 Example Outputs
Sentiment distribution charts

Word clouds for positive/negative reviews

Bigram & trigram visualizations

Cluster dendrograms

PCA/t-SNE review grouping

Product-wise & platform-wise sentiment comparisons

🎯 Business Applications
Identify product quality issues (e.g., sesame seeds receiving more negatives)

Compare sentiment across platforms (Amazon vs Flipkart vs BigBasket)

Detect customer concerns about freshness, packaging, or delivery

Support decision-making for product improvement and marketing strategy

📝 Future Enhancements
Larger dataset covering more seed types & platforms

Automated scraping pipeline

Aspect-based sentiment analysis (taste, freshness, packaging)

Interactive dashboards using Streamlit / Power BI

Support for multilingual review analysis

📄 License
This project is under the MIT License.
