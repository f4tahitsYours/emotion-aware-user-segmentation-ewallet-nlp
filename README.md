# Emotion-Aware User Segmentation of Indonesian E-Wallet Applications  
### Using NLP, Topic Modeling, and Unsupervised Learning

## 📌 Project Overview
This project aims to perform **user segmentation** on Indonesian e-wallet applications
based on **user reviews**, by leveraging **Natural Language Processing (NLP)**,
**emotion-aware sentiment analysis**, **topic modeling**, and **unsupervised learning** techniques.

Unlike traditional sentiment analysis, this study incorporates **emotional signals and topic distributions**
to uncover **latent behavioral segments** of users.

The entire pipeline is implemented and executed using **Google Colab**.

---

## 🎯 Research Objectives
- To analyze user opinions from Indonesian e-wallet applications using NLP
- To detect sentiment and emotional patterns in user reviews
- To identify dominant discussion topics using topic modeling
- To segment users into meaningful clusters using unsupervised learning
- To interpret and visualize user segments for research and business insights

---

## 📂 Project Structure

```text
ewallet_nlp_clustering_project/
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
│   ├── cluster_profile_summary.csv
│   └── final_results_with_clusters.csv
│
└── README.md
