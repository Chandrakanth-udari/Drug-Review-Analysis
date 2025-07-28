# Drug Review Sentiment Analysis

##  Objective
To analyze drug reviews from WebMD and predict sentiment (positive or negative) based on textual reviews using Natural Language Processing (NLP) techniques and a Naïve Bayes classifier.

---

##  Dataset

- **Source**: [Kaggle - WebMD Drug Reviews Dataset](https://www.kaggle.com/datasets/rohanharode07/webmd-drug-reviews-dataset)
- **Content**: Drug reviews with the following columns:
  - `drugName`
  - `condition`
  - `review`
  - `rating`
  - `date`
  - `usefulCount`

---

##  Tools & Libraries Used

- Python
- Pandas, NumPy
- NLTK, re (Regular Expressions)
- Scikit-learn
- Seaborn, Matplotlib, WordCloud

---

##  Data Preprocessing

- Removed null values and duplicate records
- Cleaned review text: lowercased, removed punctuation, stop words, and tokenized
- Used **TF-IDF Vectorization** for feature extraction

---

##  Model Building

- Applied **Multinomial Naïve Bayes Classifier**
- Converted ratings into sentiment:
  - **Positive**: Rating ≥ 7
  - **Negative**: Rating < 7
- Trained on TF-IDF vectors

---

##  Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report

---

##  Visualizations

- WordCloud for Positive and Negative reviews
- Count plots of ratings and useful counts
- Heatmaps of correlation

---

##  Files Included

- `Drug_Review_Analysis.ipynb`: Complete Jupyter notebook
- `Drug_Review_Presentation.pptx`: Visual summary of findings and methodology

---


Created by **Chandrakanth Yadav Udari**  
📧 Email: [udarichandrakanth@gmail.com](mailto:udarichandrakanth@gmail.com)  
🔗 LinkedIn: [Chandrakanth Yadav Udari](https://www.linkedin.com/in/chandrakanth-yadav-udari-a1376a32b/)


