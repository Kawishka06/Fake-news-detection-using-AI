# 📰 Fake News Detection Using NLP (TF-IDF) + Machine Learning (SVM / Logistic Regression)

A machine learning project that classifies news articles as **FAKE** or **REAL** using **Natural Language Processing (NLP)** and supervised learning models.  
The pipeline includes text preprocessing, **TF-IDF** feature extraction, model training, and evaluation with standard classification metrics.

---

## 🚀 Features
- Text cleaning and preprocessing (lowercasing, removing URLs/symbols, whitespace normalization)
- **TF-IDF Vectorization** for feature extraction
- Trained and compared:
  - **Logistic Regression**
  - **Support Vector Machine (Linear SVM)**
- Evaluation:
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix
- Model saving for future inference (`joblib`)

---

## 🧠 Models Used

### Logistic Regression
Learns a linear decision boundary and can output probabilities (when using `predict_proba`).

### Support Vector Machine (SVM)
Finds an optimal separating hyperplane by maximizing the margin between classes (high performance on text TF-IDF features).

---

## 📊 Results
> Replace the values below with your actual results.

| Model | Accuracy | F1 Score |
|------|----------|----------|
| Logistic Regression | XX.XX% | XX.XX% |
| Linear SVM | XX.XX% | XX.XX% |

---

## 🗂 Dataset
This project works with common fake news datasets (e.g., **True.csv** and **Fake.csv**) where each row contains:
- `title` (optional)
- `text` (news content)
- `label` (0 = Fake, 1 = Real) *(or created during merge)*

---

## ⚙️ Installation

### 1) Clone the repository
```bash
git clone https://github.com/Kawishka06/fake-news-detection.git
cd fake-news-detection

### 2) Install dependencies
pip install -r requirements.txt


