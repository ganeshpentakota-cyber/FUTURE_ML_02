# 🎫 Support Ticket Classification System
### Future Interns — Machine Learning Internship | Task 2

---

## 📌 Project Overview
This project builds an ML system that automatically classifies
customer support tickets into categories and assigns priority
levels — helping support teams respond faster and smarter.

---

## 🗂️ Dataset
- **Total Tickets:** 150 support tickets
- **Categories:** 5 (Billing, Technical, Account, Feature Request, General Inquiry)
- **Priority Levels:** 3 (High, Medium, Low)
- **Distribution:** 30 tickets per category, perfectly balanced

---

## ⚙️ Methodology

### 1. Text Preprocessing
- Lowercasing and special character removal
- Stopword removal using NLTK
- Lemmatization using WordNetLemmatizer
- TF-IDF vectorization with n-grams (1,3)

### 2. Models Used
| Model | Purpose |
|-------|---------|
| Logistic Regression | Category Classification |
| Logistic Regression | Priority Classification |
| TF-IDF Vectorizer | Feature Extraction |

### 3. Pipeline
