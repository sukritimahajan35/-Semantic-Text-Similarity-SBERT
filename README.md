# -Semantic-Text-Similarity-SBERT
This project explores semantic text similarity, clustering, and query-based retrieval using Sentence-BERT (SBERT). It processes the SNLI dataset, extracts sentence embeddings, and applies ML techniques for analysis. Features include cosine similarity, K-Means clustering, PCA visualization, and diverse query-based retrieval.

Key Features
🔹 Dataset Preprocessing
Loaded the SNLI dataset and extracted premises, hypotheses, and labels.
Removed missing values and performed class balancing using resampling techniques.
🔹 Sentence Embeddings with SBERT
Used three different Sentence-BERT models to generate sentence embeddings:

all-MiniLM-L6-v2 – Optimized for efficient sentence embeddings.
paraphrase-MiniLM-L6-v2 – Fine-tuned for paraphrase detection.
all-distilroberta-v1 – Uses DistilRoBERTa, a lighter alternative to RoBERTa.
🔹 Semantic Similarity Analysis
Computed cosine similarity between premise-hypothesis pairs.
Retrieved top-N similar sentences for a given query.
Visualized embedding differences between premise-hypothesis pairs.
🔹 Sentence Clustering & Visualization
Applied K-Means clustering to categorize sentence embeddings into groups.
Used PCA to reduce dimensions and visualize clusters.
🔹 Interactive Query-Based Retrieval
Implemented query embedding to find the most semantically similar sentences from the dataset.
Ensured diversity in retrieval by avoiding duplicate results.
Technologies Used
Python, scikit-learn, matplotlib, seaborn
Hugging Face Datasets & Transformers
SentenceTransformers Library
XGBoost (for future classification tasks)
