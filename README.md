# 🧠 Mental Health Text Classifier  
### NLP & Machine Learning Project

---

## 📌 Project Overview
This project applies **Natural Language Processing (NLP)** techniques to classify short text into five emotional categories:

- Depression  
- Anxiety  
- Frustration  
- Restless  
- Positive  

The system demonstrates how machine learning can be used for early-stage mental health text analysis.

---

## 🛠 Tech Stack

| Category | Tools Used |
|----------|------------|
| Language | Python |
| NLP | TF-IDF Vectorizer |
| ML Model | Multinomial Naive Bayes |
| Libraries | Scikit-learn, Pandas, Matplotlib |
| Interface | ipywidgets |

---

## 📊 Dataset

- Synthetic dataset generated using seed sentences  
- Template-based data augmentation  
- 120 total samples (24 per class)  
- Balanced multi-class distribution  

---

## 🧠 Model Architecture

Text Input

↓

TF-IDF Vectorization (Unigram + Bigram)

↓

Multinomial Naive Bayes

↓

Emotion Prediction + Probability Output


---

## 📈 Results

| Metric | Value |
|--------|--------|
| Accuracy | ~50% |
| Best F1 Score | 0.57 (Depression) |
| Train/Test Split | 80% / 20% |

> Note: Performance is limited due to small synthetic dataset size.

---

## 💡 Key Features

✔ Multi-class emotion detection  
✔ Probability distribution output  
✔ Bar chart visualization  
✔ Interactive input interface  
✔ Session history tracking  

---

## 📂 Repository Contents

- `Mental_Health_Classifier.ipynb` → Full implementation  
- `project_python.pdf` → Detailed project report  

---

## 🚀 Future Improvements

- Use real-world social media datasets  
- Compare with Logistic Regression & SVM  
- Implement Deep Learning models (LSTM / BERT)  
- Deploy as a web application  

---

## 👩‍💻 Presented By-

**Samiha Jahan Ema**  
CSE 466 – Project  
East Delta University
