**📰 Article Recommendation System using Machine Learning**

This project builds a content-based article recommendation system that suggests similar articles using Natural Language Processing (NLP) and Cosine Similarity.

**🔍 Overview**

With the huge amount of content available online, users often struggle to find relevant articles. This project demonstrates how machine learning can recommend articles based on their text similarity, without needing user history.

The system analyzes article titles and finds other articles with similar content.

**🗂 Dataset**

The dataset contains article-related information:

Article ID

Title

Category

Tags

Author

Publish Date

Views & Likes

Estimated Reading Time

Feature used for similarity: Article Title (text data)

The text data is cleaned and converted into numerical form for modeling.

**⚙️ Technologies**

Python

Pandas

NumPy

Scikit-learn

TF-IDF Vectorizer

Cosine Similarity

Google Colab

**🤖 Model**

A TF-IDF (Term Frequency–Inverse Document Frequency) model is used to convert article titles into numerical vectors.
Cosine Similarity is then applied to measure how similar articles are to each other.

This is a Content-Based Filtering approach.

**📊 Workflow**

Load article dataset

Clean text data

Convert text to numerical vectors using TF-IDF

Compute similarity scores using cosine similarity

Find and recommend the most similar articles

**🚀 Output**

When a user provides an article title, the system recommends the top similar articles based on textual content.

Example:

Input:
Advanced Python Tricks

Recommended Articles:

Building REST APIs

Intro to Machine Learning

Data Science Career Guide

Deep Learning Basics

Cloud Computing Explained
