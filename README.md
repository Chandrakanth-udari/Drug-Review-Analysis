# Drug Review Sentiment Analysis

## 📌 Objective
To analyze drug reviews from WebMD and predict sentiment (positive or negative) based on textual reviews using Natural Language Processing (NLP) techniques and a Naïve Bayes classifier.

---

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+(Drugs.com))  
- **Content**: 360,000+ drug reviews with the following columns:
  - `drugName`
  - `condition`
  - `review`
  - `rating`
  - `date`
  - `usefulCount`

---

## 🔧 Tools & Libraries Used

- Python
- Pandas, NumPy
- NLTK, re (Regular Expressions)
- Scikit-learn
- Seaborn, Matplotlib, WordCloud

---

## 🧹 Data Preprocessing

- Removed null values and duplicate records
- Cleaned review text: lowercased, removed punctuation, stop words, and tokenized
- Used **TF-IDF Vectorization** for feature extraction

---

## 🧠 Model Building

- Applied **Multinomial Naïve Bayes Classifier**
- Converted ratings into sentiment:
  - **Positive**: Rating ≥ 7
  - **Negative**: Rating < 7
- Trained on TF-IDF vectors

---

## ✅ Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📈 Visualizations

- WordCloud for Positive and Negative reviews
- Count plots of ratings and useful counts
- Heatmaps of correlation

---

## 📎 Output & Results

- Achieved ~85% accuracy in predicting drug review sentiment
- Positive reviews commonly included words like “relief”, “effective”
- Negative reviews often included “side effects”, “pain”, etc.

---

## 📁 Files Included

- `Drug_Review_Analysis.ipynb`: Complete Jupyter notebook
- `drug_reviews.csv`: Cleaned dataset (optional)
- `Drug_Review_Presentation.pptx`: Visual summary of findings and methodology

---

## 🔗 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drug-review-analysis.git
   cd drug-review-analysis


---

## 📬 Contact

Created by [Your Name]  
Feel free to connect: [your.email@example.com](mailto:your.email@example.com) | [LinkedIn](https://linkedin.com/in/yourprofile)

