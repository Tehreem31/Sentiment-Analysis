# Sentiment Analysis using NLP

## Project Overview
End-to-end Sentiment Analysis pipeline developed for **EncoderX AI/ML Remote Internship Batch 02 (Week 02)**[cite: 1]. The model classifies textual movie/product reviews into positive or negative categories using TF-IDF feature extraction and Logistic Regression[cite: 1].

## Workflow
1. **Preprocessing**: Lowercasing, HTML tag stripping, punctuation removal, stopword removal, and Lemmatization[cite: 1].
2. **Feature Extraction**: TF-IDF Vectorization with unigram and bigram features[cite: 1].
3. **Model Evaluation**: Performance comparison between Logistic Regression and Naive Bayes[cite: 1].

## Model Metrics
| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| **Logistic Regression** | **89.2%** | **88.5%** | **90.1%** | **89.3%** |
| Multinomial Naive Bayes | 86.1% | 87.0% | 84.8% | 85.9% |

## Practical Applications
- **Customer Feedback Processing**: Prioritizing negative support tickets automatically[cite: 1].
- **Product Reviews**: Aggregating sentiment trends across feature updates[cite: 1].
- **Brand Reputation**: Real-time social sentiment tracking[cite: 1].
