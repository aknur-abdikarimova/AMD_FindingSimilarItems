# Finding Similar Items — Amazon Books Reviews

This project detects duplicate and near-duplicate book reviews in the Amazon Books Reviews dataset using text similarity techniques.
It combines shingling, MinHash, and Locality-Sensitive Hashing (LSH) to efficiently approximate Jaccard similarity across millions of reviews.

### Project Overview

Dataset: *Amazon Books Reviews (Kaggle)*

Goal: Identify repeated, copied, or rephrased reviews to improve data quality and reduce redundancy.

### Core Methods:

Text preprocessing and normalization (tokenization, lemmatization, stopword removal)

Shingling for text representation

MinHash for efficient signature generation

LSH for scalable similarity search

Exact Jaccard verification for candidate pairs

### Results

Over 800 duplicate or near-duplicate pairs detected.

Most duplicates are identical reviews or re-posted across editions.

Review scores remain highly consistent within duplicate groups.

### Tools & Libraries

Python, pandas, NumPy

nltk, langdetect, mmh3

datasketch for MinHash and LSH

Matplotlib / Seaborn for visualizations

LaTeX for the project report

### Key Insight

Efficient text deduplication using MinHash–LSH significantly reduces computational cost while preserving accuracy, making it ideal for large-scale text analytics and recommendation systems.
