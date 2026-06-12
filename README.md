# BullyNet: Detecting Digital Harassment using NLP & Machine Learning

## 📌 Project Overview

BullyNet is a Natural Language Processing (NLP) and Machine Learning based system that detects cyberbullying and digital harassment in online text.
The system analyzes user comments and classifies them into different categories such as gender-based harassment, age-based harassment, religion-based harassment, ethnicity-based harassment, general cyberbullying, or non-bullying content.

This project aims to support safer online communities by assisting content moderation systems.

---

## 🎯 Objectives

* Detect cyberbullying in digital text.
* Classify harassment into multiple categories.
* Apply NLP preprocessing techniques for text analysis.
* Compare machine learning models for better classification accuracy.

---

## ⚙️ Technologies Used

* Python
* Natural Language Processing (NLP)
* Scikit-learn
* NLTK / spaCy
* Streamlit / Flask
* Pandas
* NumPy

---

## 🧠 Algorithms Used

The following machine learning algorithms were used for classification:

* Logistic Regression
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

---

## 🔍 NLP Techniques Used

To process and analyze text data, the following NLP techniques were applied:

* Tokenization
* Stemming
* Lemmatization
* TF-IDF Vectorization
* Word Embeddings

---

## 🗂️ Harassment Categories Detected

The model classifies text into the following categories:

* Age-based harassment
* Gender-based harassment
* Ethnicity-based harassment
* Religion-based harassment
* General cyberbullying
* Not cyberbullying

---

## 🏗️ System Workflow

1. User inputs a comment.
2. Text preprocessing is applied (tokenization, cleaning).
3. Text is converted into numerical features using TF-IDF.
4. Machine learning models classify the comment.
5. The system outputs the predicted category.

---

## 📂 Project Structure

```
bullynet-cyberbullying-detection
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── dataset.csv
├── requirements.txt
├── README.md
│
├── templates
│   └── index.html
│
└── static
    └── style.css
```

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/bullynet-cyberbullying-detection
```

2. Navigate to the project directory

```
cd bullynet-cyberbullying-detection
```

3. Install required libraries

```
pip install -r requirements.txt
```

4. Run the application

```
python app.py
```

---

## 🚀 Future Improvements

* Support for multiple languages
* Detection of bullying in images and videos
* Integration with deep learning models like BERT
* Real-time social media monitoring

---

## 📚 References

* Research papers on cyberbullying detection using NLP and Machine Learning.
* Online datasets and academic publications related to digital harassment detection.

---

## 👩‍💻 Authors

* Anjali Kumari
* Mohd Aqib Ali
* Syed Abdul Jabbar

Department of CSE – Artificial Intelligence & Machine Learning
