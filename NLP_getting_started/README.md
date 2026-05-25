<div align="center">
  <h1>🚨 NLP Getting Started: Disaster Tweets Analysis</h1>
  <p><i>The first practical dive into Natural Language Processing (NLP).</i></p>

  <p>
    <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
    <img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy" />
  </p>
  <p>
    <b>Prepared by KevJoss</b>
  </p>
</div>

---

## 🎯 Goal
Work with the Kaggle **"Disaster Tweets"** dataset to perform text preprocessing, detailed exploratory data analysis, and establish a baseline classification model. 

## 📁 Folder Contents

### 📓 `EDA_tweet_disaster_task_1.ipynb`
A comprehensive, step-by-step Exploratory Data Analysis (EDA) notebook focusing on understanding the dataset in depth.
* **🔍 Dataset Overview:** Structure, missing values, and class distribution.
* **🧹 Text Quality & Cleaning:** Identifying duplicates, handling empty entries, and cleaning metadata (URLs, mentions, HTML entities).
* **📈 Lexical & Surface-Level Analysis:** Examining n-gram frequencies, hashtag co-occurrence matrices, stopword impact, and emotional intensity signals (punctuation and capitalization ratios).

### 📓 `Tweet_disaster_mini_EDA.ipynb`
A concise, end-to-end pipeline notebook.
* **📊 Mini EDA:** Exploring class distributions, tweet character lengths, and word counts.
* **🧠 Modeling:** Setting up text preprocessing and tokenization to train an introductory Deep Learning (Neural Network) classifier.

### 💾 `data/`
Subdirectory for the base `.csv` files used as the information source for the notebooks.

---

## 📝 Summary
This space documents how to take **"raw" and "imperfect" text data from social media**, explore it statistically (from surface-level metadata to deep lexical analysis), polish it, and finally prepare the corpus for training algorithms like Neural Networks.
