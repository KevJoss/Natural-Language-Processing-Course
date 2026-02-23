# NLP Getting Started: Disaster Tweets Analysis

This folder marks the first practical dive into Natural Language Processing (NLP). The main goal is to work with a Kaggle dataset of "Disaster Tweets", performing the step-by-step process prior to classification.

## Folder Contents

* **`EDA_tweet_disaster_task.ipynb`**: The main workspace file. It is a Jupyter Notebook containing the analysis and modeling. The tasks covered include:
  * **Exploratory Data Analysis (EDA):** Understanding the language distribution (average characters per tweet, length histograms, WordClouds, and *stopwords* analysis).
  * **Data Cleaning:** Removing and resolving duplicated or contradictory records (same tweet, different labels), extracting invalid characters (line breaks and URLs), and sanitizing the corpus.
* **`data/`**: Subdirectory for the base `.csv` files used as the information source for the notebook.

In summary: This space documents how to take **"raw" and "imperfect" text data from social media**, explore it statistically, and polish it until it is mathematically structured and ready for any neural network.
