# Drug Review Sentiment Analysis

This project analyzes patient reviews for various drugs using NLP (Natural Language Processing) and machine learning. It predicts user satisfaction ratings based on review text using a Naïve Bayes classifier. Visualizations and exploratory analysis highlight how gender, age, and drug types affect satisfaction.

## 📊 Project Overview

- **Dataset Source:** [WebMD Drug Reviews - Kaggle](https://www.kaggle.com/datasets/rohanharode07/webmd-drug-reviews-dataset)
- **Total Records:** 360,000+ unique drug reviews
- **Goal:** Predict satisfaction rating (negative, neutral, positive) based on patient reviews

## 🧠 Techniques Used

- Text Cleaning & Preprocessing
- Stopword Removal, Stemming
- TF-IDF Vectorization
- Naïve Bayes Classification
- Word Cloud & Data Visualization
- Confusion Matrix & Accuracy Evaluation

## 🗂️ Project Structure

| File/Folder               | Description                                  |
|---------------------------|----------------------------------------------|
| `Drug_Review_Analysis.ipynb` | Main notebook with code, EDA, NLP & ML      |
| `Drug_Review_Analysis_Presentation.pptx` | Slide deck summarizing project        |
| `images/`                 | Word clouds, heatmaps, visual output images  |
| `data/`                  | Sample data or CSV file (avoid large files)  |
| `README.md`               | Project overview and instructions            |

## 🛠️ Libraries Used

- Python 3.x
- Pandas, NumPy
- NLTK, Scikit-learn
- Matplotlib, Seaborn
- WordCloud

## 📌 Model Summary

The Naïve Bayes classifier achieved strong performance by vectorizing cleaned review text with TF-IDF. Ratings were categorized as:
- 1–2 → Negative (0)
- 3   → Neutral  (1)
- 4–5 → Positive (2)

The model was evaluated using a confusion matrix and standard metrics (accuracy, precision, recall).

## 📷 Sample Visualizations

![Word Cloud](images/wordcloud.png)
![Heatmap](images/heatmap.png)

## 🔗 Dataset

Due to size, the full dataset is not included. You can download it here:  
📎 [WebMD Drug Reviews – Kaggle](https://www.kaggle.com/datasets/rohanharode07/webmd-drug-reviews-dataset)

## 📽️ Presentation

A summary PowerPoint of the project is included in the repository for quick review of objectives, techniques, visuals, and conclusions.

---

## 💡 Inspiration

With rising drug costs and heavy usage in the U.S., sentiment analysis of patient reviews helps identify patterns in drug effectiveness and side effects. This project helps visualize and predict patient satisfaction using real-world medical feedback.

---

## 📬 Contact

Created by [Your Name]  
Feel free to connect: [your.email@example.com](mailto:your.email@example.com) | [LinkedIn](https://linkedin.com/in/yourprofile)

