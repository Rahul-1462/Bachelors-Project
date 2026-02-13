# Toxic Comment Classification Using NLP and Logistic Regression

This project implements an automated system to detect toxic comments using Natural Language Processing (NLP) techniques and a Logistic Regression classifier.  
The goal is to identify harmful language such as hate speech, cyberbullying, and offensive comments to support safer online communities.

---

## Project Overview

With the rapid growth of social media, toxic comments have become a major challenge for online platforms.  
This system preprocesses textual data, extracts meaningful features using TF-IDF and n-grams, handles class imbalance using SMOTE, and trains a Logistic Regression model to classify comments as:

- 1 → Toxic  
- 0 → Non-Toxic  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- NLTK  
- TextBlob  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Matplotlib  
- Jupyter Notebook  


## Methodology

1. Text Preprocessing  
   - Lowercasing  
   - Removing punctuation and special characters  
   - Stop-word removal  
   - Lemmatization  

2. Feature Extraction  
   - TF-IDF Vectorization  
   - N-grams (bi-grams, tri-grams)  
   - Sentiment polarity  

3. Handling Imbalanced Data  
   - SMOTE oversampling  

4. Model Training  
   - Logistic Regression classifier  

5. Evaluation  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  

---

## How to Run

1. Install required libraries

pip install pandas numpy nltk scikit-learn imbalanced-learn textblob matplotlib

2. Open Jupyter Notebook

jupyter notebook

3. Run the notebook

toxic_comment_classification.ipynb

---

## Sample Output

Input:
"good video"  
"bad video"  
"ravi is a bad guy"  

Output:
Non-Toxic  
Toxic  
Toxic  

---

## Documentation

Detailed explanation of problem statement, literature review, system architecture, methodology, and results is available in the docs folder.

