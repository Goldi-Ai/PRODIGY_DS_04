# PRODIGY_DS_04 - Sentiment Analysis on Social Media Data

Overview:
This project performs Sentiment Analysis on Twitter data using machine learning techniques. The goal is to classify tweets into three sentiment categories: Positive, Negative, and Neutral. This analysis provides insights into public opinion, which can be valuable for various applications such as brand monitoring, product feedback analysis, and market research.

Dataset

The dataset used in this project contains tweets with labels indicating their sentiment. The file twitter_training.csv is used as the primary dataset, which consists of two columns:

Sentiment: The sentiment label (Positive, Negative, or Neutral).

Tweet: The text of the tweet.

Steps Involved:
1. Data Preprocessing

Text Cleaning: Remove stopwords, punctuation, and special characters.

Text Normalization: Convert text to lowercase to avoid case sensitivity issues.

2. Data Exploration and Visualization

Sentiment Distribution: Visualized the distribution of sentiments in the dataset using bar charts.

Word Clouds: Created word clouds for each sentiment class to identify the most frequent terms associated with each sentiment.

3. Feature Extraction

TF-IDF Vectorization: Applied TF-IDF Vectorizer to convert text data into numerical features for model training.

4. Model Training and Evaluation

Model 1: Trained Naive Bayes model and evaluated its performance.

Model 2: Trained Logistic Regression model and compared its performance with Naive Bayes.

Performance Metrics: The models were evaluated using accuracy and F1-score. Confusion matrices were also plotted to analyze model performance.

5. Comparison

Naive Bayes vs Logistic Regression: Compared both models based on accuracy and F1-score, and concluded that Logistic Regression performed better in this case.

#Requirements:

Python 3.x

Libraries:

pandas

numpy

matplotlib

seaborn

wordcloud

scikit-learn

nltk

bash
pip install pandas numpy matplotlib seaborn wordcloud scikit-learn nltk

#How to Run
Clone the repository:
git clone https://github.com/<your-username>/Sentiment-Analysis-Twitter.git
Install the necessary dependencies:
bash
pip install -r requirements.txt
#Run the Jupyter Notebook (sentiment_analysis.ipynb) to execute the code and generate results.
bash
jupyter notebook sentiment_analysis.ipynb

##Ensure that the dataset file twitter_training.csv is placed inside the dataset/ folder.

#Results

Sentiment Distribution: Visualized the sentiment distribution as a bar chart.

WordCloud: Created word clouds for positive, negative, and neutral tweets.

Model Performance:

Logistic Regression performed better with an accuracy of XX% and an F1-score of YY.

Naive Bayes showed decent performance but was outperformed by Logistic Regression.

#Conclusion

This project demonstrates the use of basic machine learning models for sentiment analysis on text data. Logistic Regression provided the best performance for this task. Future work may involve exploring deep
learning models (e.g., LSTM) for even higher accuracy.

#Directory Structure:

Sentiment-Analysis-Twitter/


├── dataset/
│   └── twitter_training.csv        
├── sentiment_analysis.ipynb        
├── README.md                      
└── requirements.txt               
