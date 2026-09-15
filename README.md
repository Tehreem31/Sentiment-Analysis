# Sentiment Analysis using Natural Language Processing (NLP)

**EncoderX AI / Machine Learning Remote Internship — Batch 02 (Week 02)**

---

## 📌 Project Deliverables
- **Jupyter Notebook**: Complete data preprocessing, feature extraction, model training, and evaluation workflow (`Sentiment_Analysis.ipynb`).
- **Source Code**: Python implementation for end-to-end sentiment classification.
- **Model Evaluation Report**: Performance evaluation including confusion matrix and training curves.
- **Project Documentation**: Workflow details, model metrics, and practical applications.
- **GitHub Repository Link**: Public codebase containing all project assets.

---

## 🛠️ Project Workflow

### 1. Dataset Selection
Utilized movie and product review text data for binary sentiment classification (Positive / Negative).

### 2. Text Preprocessing
- HTML tag stripping and noise removal
- Lowercasing and tokenization
- Stopword removal (retaining key negations)
- Lemmatization

### 3. Feature Extraction
Transformed unstructured text into numerical features using **TF-IDF (Term Frequency - Inverse Document Frequency)** vectorization.

### 4. Model Evaluation
Evaluated baseline and classification models on test datasets.

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| **Logistic Regression** | **89.2%** | **88.5%** | **90.1%** | **89.3%** |
| Multinomial Naive Bayes | 86.1% | 87.0% | 84.8% | 85.9% |

---

## 💡 Practical Business Applications
- **Customer Feedback Processing**: Automating negative feedback prioritization.
- **Product Reviews**: Tracking sentiment trends across product updates.
- **Brand Reputation**: Real-time social media sentiment monitoring.

---
