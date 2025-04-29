# Sentiment Analysis: Jake Paul vs Mike Tyson Fight Comments

This project performs sentiment analysis on YouTube comments related to the Jake Paul vs Mike Tyson boxing match. Using Natural Language Processing (NLP) techniques and machine learning, we clean, explore, and classify comments into **positive**, **negative**, or **neutral** sentiments to understand public reaction to the event.

---

# Objective

To analyze public opinion around the fight by:
- Cleaning raw YouTube comments.
- Visualizing the distribution of sentiments.
- Building a classification model to predict sentiment.
- Evaluating model performance using standard metrics.

---

# Project Highlights

- ✅ Preprocessing of unstructured text data (cleaning, tokenization, stopword removal).
- ✅ Data visualization using bar charts and word clouds.
- ✅ Sentiment classification using **Logistic Regression**.
- ✅ Performance evaluation via confusion matrix and classification report.

---

# Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- NLTK
- Matplotlib & Seaborn
- Scikit-learn
- WordCloud
- Emoji

---

# Text Preprocessing

The following cleaning steps were applied to the comments:
- Removed URLs, mentions, hashtags, and emojis.
- Converted text to lowercase.
- Removed punctuation and non-alphanumeric characters.
- Tokenized and removed stopwords using NLTK.

---

# Exploratory Data Analysis

- A **bar chart** shows the distribution of sentiments across the dataset.
- **Word clouds** were generated to visualize the most common terms for each sentiment category:
  - Positive comments: praise, excitement, appreciation.
  - Negative comments: criticism, sarcasm, disappointment.
  - Neutral comments: facts, questions, general talk.

---

# Sentiment Classification

- Model used: **Logistic Regression** from scikit-learn.
- Features extracted using basic bag-of-words approach.
- Achieved good balance across all three sentiment classes.
- Evaluation:
  - **Confusion Matrix**
  - **Precision / Recall / F1 Score**

# Credits

- This project is done by **Kumar Manik**.
