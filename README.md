# Emotion-Aware User Segmentation of Indonesian E-Wallet Applications
### Using NLP, Topic Modeling, and Unsupervised Learning

## 📌 Project Overview
This project focuses on **emotion-aware user segmentation** for Indonesian e-wallet applications by analyzing user reviews from Google Play Store. The study applies **Natural Language Processing (NLP)**, **sentiment and emotion analysis**, **topic modeling**, and **unsupervised machine learning** to uncover latent user behavior patterns.

Rather than relying solely on star ratings or polarity sentiment, this research integrates **emotional signals and topic distributions** to generate more meaningful and interpretable user clusters.

All experiments, analysis, and visualizations are conducted entirely in **Google Colab**.

---

## 🎯 Research Objectives
- Analyze Indonesian e-wallet user reviews using NLP techniques
- Identify sentiment polarity and dominant emotions in user feedback
- Extract latent discussion themes via topic modeling
- Segment users into interpretable clusters using unsupervised learning
- Provide research and business insights based on cluster characteristics

---

## 📂 Project Structure

```
ewallet-nlp-clustering-project/
├── notebooks/
│   ├── 01_data_scraping.ipynb
│   ├── 02_text_preprocessing.ipynb
│   ├── 03_sentiment_emotion_analysis.ipynb
│   ├── 04_topic_modeling_bertopic.ipynb
│   ├── 05_feature_engineering.ipynb
│   ├── 06_clustering_modeling.ipynb
│   ├── 07_clustering_evaluation.ipynb
│   └── 08_cluster_analysis_and_results_interpretation.ipynb
│
├── data/
│   ├── raw/
│   └── processed/
│
├── outputs/
│   ├── final_results_with_clusters.csv
│   └── cluster_profile_summary.csv
│
└── README.md
```

---

## 📊 Dataset Description
- **Source**: Google Play Store reviews
- **Domain**: Indonesian e-wallet applications
- **Total Reviews**: ±15,000
- **Language**: Indonesian
- **Time Span**: Multi-year

### Dataset Schema
| Column | Description |
|------|------------|
| review_id | Unique identifier |
| app_name | E-wallet application |
| review_text | Raw review text |
| rating | User rating (1–5) |
| review_date | Timestamp |
| sentiment_score | Polarity score |
| emotion_label | Dominant emotion |
| emotion_* | Emotion features (encoded) |
| topic_id | Topic from BERTopic |
| cluster_kmeans | Final cluster label |

---

## 🧪 Methodology & Notebook Description

### 1️⃣ Data Scraping (`01_data_scraping.ipynb`)
- Automated scraping of Google Play Store reviews
- Multi-application and multi-period collection
- Data validation and deduplication

### 2️⃣ Text Preprocessing (`02_text_preprocessing.ipynb`)
- Text normalization and cleaning
- Tokenization and stopword removal
- Indonesian language preprocessing
- Generation of clean textual corpus

### 3️⃣ Sentiment & Emotion Analysis (`03_sentiment_emotion_analysis.ipynb`)
- Sentiment polarity estimation
- Emotion detection (e.g., joy, anger, sadness, neutral)
- Feature encoding for downstream modeling

### 4️⃣ Topic Modeling (`04_topic_modeling_bertopic.ipynb`)
- Sentence embedding with transformer models
- Topic extraction using BERTopic
- Topic probability distribution per review

### 5️⃣ Feature Engineering (`05_feature_engineering.ipynb`)
- Feature selection and transformation
- Integration of sentiment, emotion, and topic features
- Numerical scaling and validation

### 6️⃣ Clustering Modeling (`06_clustering_modeling.ipynb`)
- Feature normalization
- K-Means clustering
- Agglomerative clustering comparison
- Optimal cluster determination

### 7️⃣ Clustering Evaluation (`07_clustering_evaluation.ipynb`)
- Silhouette score analysis
- Cluster cohesion and separation evaluation
- Model selection justification

### 8️⃣ Cluster Analysis & Research Interpretation (`08_cluster_analysis_and_results_interpretation.ipynb`)
- Cluster profiling and characterization
- Emotion and sentiment comparison across clusters
- Dominant topic identification
- Representative review sampling
- Final interpretation of research findings

---

## 📈 Key Results & Outputs
- Emotion-aware user segmentation model
- Interpretable cluster profiles
- Visualization of sentiment, emotion, and topic distributions
- Actionable insights on user behavior patterns

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- BERTopic
- Sentence-Transformers
- Matplotlib & Seaborn
- Google Colab

---

## 📌 Research Contribution
This research demonstrates that incorporating **emotion-aware NLP features** enhances traditional user segmentation approaches, enabling deeper behavioral insights for digital financial service applications.

---

## 👨‍💻 Author
**Fatahillah**  
Mahasiswa – Data Science & NLP  
Indonesia 🇮🇩

---

## 📜 License
This project is intended for academic, educational, and research purposes only.

