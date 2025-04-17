# NLP-NEWS-ARTICLE-CLASSIFIER

> Categorizing news articles using multi‑model NLP classification pipeline on 2k+ news articles using TF‑IDF and four classifier algorithms

---

## 📌 Project Overview

This project aims to automate the classification of news content into categories such as **Politics, Technology, Sports, Business, and Entertainment** using Natural Language Processing and supervised machine learning.  
The objective is to extract insights from text data, implement standard NLP preprocessing steps, and build a robust multi-class classifier pipeline that generalizes well across news topics.

---

## 🧠 Concepts Applied

- Natural Language Processing (NLP)
- Text Preprocessing  
  - Removing special characters and digits  
  - Tokenization  
  - Stopword Removal  
  - Lemmatization  
- Feature Engineering:  
  - Bag of Words  
  - TF-IDF Vectorization  
- Classification Models:  
  - Naive Bayes  
  - Decision Tree  
  - K-Nearest Neighbors  
  - Random Forest  
- Model Evaluation  
  - Accuracy  
  - Confusion Matrix  
  - Classification Report

---

## 📂 Dataset

| Feature   | Description                                       |
|-----------|---------------------------------------------------|
| `Article` | Raw textual content of news articles              |
| `Category`| Predefined label for classification (5 categories)|

📝 **Note**: Dataset provided by the academic institution as part of coursework. Source kept confidential.

---

## 🔁 Project Workflow

1. **Data Loading**
   - Imported CSV dataset
   - Verified format and data types

2. **Initial Exploration**
   - Checked dataset shape and missing values
   - Analyzed distribution across categories

3. **Data Cleaning**
   - Removed duplicate articles to avoid data leakage
   - Ensured a **balanced dataset** for fair model training

4. **Text Preprocessing**
   - Lowercasing, removing non-letters
   - Tokenization
   - Stopword removal
   - Lemmatization using `WordNetLemmatizer`
   - Displayed before/after example for clarity

5. **Feature Transformation**
   - Label encoding of target variable
   - Text vectorization using:
     - **Bag of Words**
     - **TF-IDF** (default method)

6. **Model Development**
   - Performed train-test split (75:25)
   - Trained models:
     - Naive Bayes (baseline)
     - Decision Tree
     - K-Nearest Neighbors
     - Random Forest
   - Code modularized into functions for reusability

7. **Evaluation**
   - Plotted confusion matrix
   - Printed classification reports
   - Comparative analysis of all models (to be updated)

---

## 📊 Results

🚧 _Under Evaluation — This section will be updated after optimizing model performance._

---

## ❓ Sample Questions Addressed

- How many news articles are present in the dataset?
- Which category has the most and least articles?
- What are stopwords and why are they removed?
- How does **Lemmatization** differ from **Stemming**?
- Which technique is more efficient: Bag of Words vs TF-IDF?
- What are the dimensions of the train and test datasets?
- Which model performed best? _(To be finalized)_
- Is precision as important as recall in this case? → ✅ **True**

---


## 📌 Note

This project is to demonstrate the application of **Natural Language Processing** and **Machine Learning** in solving real-world classification problems.

---
