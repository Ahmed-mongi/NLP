# NLP
# Social Media Sentiment Analysis (2010–2023)

## About Dataset
The dataset is from [Kaggle](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset/data).  
It captures emotions, trends, and interactions across social media platforms.  
Each entry includes text, timestamps, hashtags, countries, likes, and retweets.  

## Project Description
This project analyzes sentiment changes from 2010 to 2023 on social media platforms.  
It applies the standard data analysis workflow and natural language processing techniques.  

Key steps:  
- This project aims to understand sentiment changes from 2010 to 2023 on popular social media platforms based on certain attributes and how they impact each other.
- This project explores the standard procedure of data analysis, including data preprocessing, feature engineering, EDA and supervised machine learning.
- This project introduces the standard procedure of natural language processing(text clearning, word embedding, etc.), and used multiclass classification models for sentiment analysis.
- This proect optimizes text classification using pre-trained LLM model BERT, and preprocess datasets from dataframe to datasets in tensors using pytorch.
- This project leverages some popular data-analyic tools, including pandas, matplotlib, seaborn, sckiitlearn and a decent usage of natural language processing tool-nltk.

## Tools and Libraries
- **Python**  
- **pandas, matplotlib, seaborn, scikit-learn**  
- **NLTK, wordcloud**  
- **PyTorch, transformers, tqdm**  

## Getting Started
Dependencies
- The process of Analysis is stored in the Jupyter Notebook 'sentiment_analysis.ipynb'.
- Pre-req Python Libraries include: re, pandas, maplotlib, seaborn, scikitlearn, wordcloud, nltk, torch, transformers, tqdm.
- 
Executing Program
- To begin, locate jupyter notebook 'NLP.ipynb' and run all cells for results.
  
Potential Issues
- Dataset is generated using chatGPT, which can be problematic in the accuracy and reliability of this dataset.
- Based on the sentiment analysis of each post' original text, there are issues of mislabeling sentiments, which can significantly affect the sentiment analysis.
- Based on the sentiment analyzer, some positive and negaive words are mis-categorized as neutral, which can lead to overestimation of 'neutral' in any sentiment  results.
- Based on BERT's training accuracy and test accuracy after 20 epoches, the issue of overfitting still persists.

## Resources
Learning description of this dataset @https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset/data
