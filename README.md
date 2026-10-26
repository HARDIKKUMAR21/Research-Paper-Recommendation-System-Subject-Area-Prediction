# Research-Paper-Recommendation-System-Subject-Area-Prediction

A Python-based NLP project that recommends relevant research papers and predicts their academic subject areas using machine learning. The system processes a dataset of **50,000+ arXiv research papers**, applies text preprocessing and TF-IDF vectorization, and uses cosine similarity to retrieve the top 5 similar papers. It also implements a multi-class text classification model to categorize research papers across 15+ academic subject areas.

### Key Features
- **Research Paper Recommendation:** Content-based filtering using TF-IDF vectorization and cosine similarity to identify similar research papers.
- **NLP Preprocessing Pipeline:** Text tokenization, stop-word removal, lemmatization, and feature extraction using NLTK and spaCy.
- **Subject Area Prediction:** Multi-class text classification for automatically predicting academic categories of research papers.
- **Efficient Retrieval:** Optimized similarity-based retrieval with a reported query latency of under 200 ms.
- **Model Evaluation:** Comparison of three vectorization approaches using 5-fold cross-validation to evaluate recommendation relevance and classification performance.

### Tech Stack
Python • NLP • Scikit-learn • NLTK • spaCy • TF-IDF • Cosine Similarity • Text Classification

### Project Highlights
- Processed a corpus of 50,000+ research papers.
- Implemented a four-stage NLP preprocessing pipeline.
- Achieved 88.5% validation accuracy and a 0.87 macro F1-score for subject area classification.
- Improved top-5 recommendation relevance by 24% over baseline keyword matching.

### Objective
To simplify academic literature discovery by helping researchers identify relevant publications and automatically classify research papers based on their textual content.
