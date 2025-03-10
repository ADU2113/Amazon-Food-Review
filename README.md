## 2×2 Matrix TDM - Amazon Food Reviews  

This repository contains an analysis of *Amazon Fine Food Reviews* using a *2×2 Term-Document Matrix (TDM)* for sentiment classification. The goal is to predict sentiment labels and evaluate model performance using *precision, recall, and F1-score* metrics.  

---

## 📌 Dataset Overview  

The dataset used in this project is *Amazon Fine Food Reviews, available on **Kaggle*:  
📌 [Amazon Fine Food Reviews Dataset](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)  

- *1,568,454* reviews from *Amazon*  
- Includes product reviews, ratings, and sentiment labels  
- Focuses on food-related items  

For this analysis, we use a *subset* of the dataset to classify sentiment into:  
- *1 → Negative Review*  
- *2 → Positive Review*  

The model is trained on *142,114 reviews*, and performance is evaluated based on classification metrics.  

---

## 📊 Model Performance Metrics  

       precision    recall  f1-score   support

   1       0.68      0.64      0.66     20500
   2       0.94      0.95      0.94    121614

- *Overall Accuracy*: 91%
- *Macro Average (Unweighted Mean Performance Across Classes)*:  
  - Precision: 0.81  
  - Recall: 0.79  
  - F1-Score: 0.80  
- *Weighted Average (Considering Class Imbalance)*:  
  - Precision: 0.90  
  - Recall: 0.91  
  - F1-Score: 0.90  

---

## ⚡ Approach & Methodology  

- *Text Preprocessing* → Cleaning, tokenization, stopword removal  
- *Feature Extraction* → Converting text into a *Term-Document Matrix (TDM)*  
- *Model Training* → Using ML classifiers for sentiment prediction  
- *Performance Evaluation* → Assessing precision, recall, F1-score, and accuracy  

---

## 🚀 Next Steps  

- Implement *TF-IDF* instead of a basic TDM for improved representation  
- Test with advanced classifiers like *SVM, Logistic Regression, or Neural Networks*  
- Perform *hyperparameter tuning* to optimize results  
