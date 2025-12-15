# Sentiment-analysis
Sentiment analysis of persian instagram comments

## 📄 Project Overview
This mini project focuses on performing sentiment analysis on social media comments to classify them into **positive, negative, or neutral** sentiments using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

The project is designed to be **language-independent** by translating non-English text into English before analysis.

---

## 📊 Dataset Description
- **Dataset Name:** Instagram Persian Comments Dataset  
- **Source:** Kaggle  
- **Content:** User-generated Persian (Farsi) comments collected from Instagram posts.  
- **Purpose:** To analyze public sentiment expressed in social media comments.

Since the original dataset contains **Persian-language comments**, all comments were **translated into English** to ensure compatibility with standard NLP preprocessing techniques and machine learning models.

---

## 🌍 Language Independence Handling
To handle language dependency:
- Persian comments were **translated into English** using a translation approach.
- This step enabled the use of **English NLP libraries** such as NLTK.
- The translation process makes the system **scalable and adaptable** to other languages in the future.

---

## ⚙️ Methodology
1. **Data Collection** from Kaggle (Instagram Persian Comments Dataset)
2. **Language Translation** (Persian → English)
3. **Text Preprocessing**
   - Tokenization  
   - Stopword removal  
   - Normalization  
   - Lemmatization  
4. **Feature Extraction**
   - Bag of Words (BoW)  
   - TF-IDF Vectorization  
5. **Model Training**
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
   - Ensemble Models (Voting & Stacking)  
6. **Model Evaluation**
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - ROC-AUC Curve  
7. **Explainability**
   - SHAP for model interpretation  
8. **Visualization**
   - WordClouds  
   - Confusion Matrix  
   - ROC Curves  

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, NLTK, Matplotlib, SHAP, WordCloud  
- **Platform:** Jupyter Notebook  

---

## 📈 Results
The trained models demonstrated effective sentiment classification performance.  
Ensemble models showed improved accuracy and F1-score compared to individual classifiers.  
SHAP analysis helped in understanding feature importance and model decisions.

---

## ▶️ How to Run the Project

```bash
pip install -r requirements.txt

