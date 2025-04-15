# 📌 IT-Support-Ticket-Classification

Automated classification of IT support tickets using Natural Language Processing (NLP) and Machine Learning.  
Achieved **91% accuracy** and **89% F1-score** on a real-world dataset of 8,469 support tickets.

---

## 🚀 Project Overview

- **🎯 Objective:** Automatically classify IT support tickets into predefined categories.
- **📊 Dataset:** 8,469 tickets with textual descriptions.
- **🗂️ Categories:**
  1. Refund Request  
  2. Technical Issue  
  3. Cancellation Request  
  4. Product Inquiry  
  5. Billing Inquiry
- **✅ Accuracy Achieved:** 91%
- **🏅 F1-score:** 89%

---

## 🔍 Key Features

- **🧹 Preprocessing:**
  - Stop word removal, tokenization, lemmatization
  - TF-IDF vectorization for feature extraction

- **🤖 ML Models Used:**
  - Logistic Regression
  - Random Forest
  - Naive Bayes

- **⚙️ Hyperparameter Tuning:**
  - GridSearchCV and RandomizedSearchCV

- **📚 Topic Modelling:**
  - NMF (Non-negative Matrix Factorization)
  - Used for exploratory topic discovery and category refinement

- **📊 Model Evaluation:**
  - Metrics: Accuracy, Precision, Recall, F1-score
  - Confusion matrix for visual error analysis

- **📈 Visualizations:**
  - Word clouds by category
  - Term frequency bar charts
  - Confusion matrix heatmap

---

## 🛠️ Tech Stack

- Python 🐍  
- Libraries: `pandas`, `scikit-learn`, `nltk`, `spaCy`, `transformers`, `matplotlib`, `seaborn`  
- Jupyter Notebooks 📓  

---

## 📈 Results & Insights

- Naive Bayes outperformed both models in both accuracy and recall.
- Most confusion occurred between similar categories (e.g., Billing vs Refund).
- NMF uncovered latent topics, suggesting possible category refinement.

---

## 🔄 Next Steps

- [ ] Deploy best model using Flask or FastAPI
- [ ] Integrate with live ticketing systems (e.g., Zendesk, Freshdesk)
- [ ] Add multi-label classification support
- [ ] Explore few-shot classification with LLMs (e.g., GPT, T5)

---
