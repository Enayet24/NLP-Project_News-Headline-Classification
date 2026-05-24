# 📰 News Headline Classification: A Comparative Analysis

## 📘 Overview

This project presents a comprehensive comparative analysis of **multi-class text classification** using the **AG News dataset**. The study evaluates the impact of different **preprocessing strategies**, **word representation techniques**, and **model architectures** on classification performance.

A total of **24 experimental configurations** were conducted by combining:

- 3 preprocessing strategies  
- 2 word representation techniques  
- 8 model architectures

---

## 🎯 Objectives

The main objectives of this project are:

- To perform multi-class classification on news headlines  
- To compare preprocessing techniques and their impact on performance  
- To evaluate TF-IDF vs embedding-based representations  
- To benchmark machine learning and deep learning models  
- To identify the best-performing model configuration  

---

## 🗂️ Dataset

- **Dataset:** AG News Dataset  
- **Task:** Multi-class classification (4 categories)  
- **Data Split:** Predefined training and testing sets  

The dataset consists of short news headlines, making it suitable for evaluating both traditional and neural NLP models.

---

## 🧹 Preprocessing Strategies

Three different preprocessing pipelines were implemented:

### 🔹 No Preprocessing
- Raw text used directly  
- No cleaning or normalization  

### 🔹 Extreme Preprocessing
- Lowercasing  
- Stopword removal  
- HTML removal  
- Stemming (Porter Stemmer)  
- Aggressive cleaning  

### 🔹 Optimum Preprocessing
- Lowercasing  
- HTML removal  
- Stopword removal  
- WordNet lemmatization  
- Balanced cleaning based on EDA insights  

---

## 🧠 Word Representation Techniques

### 📊 TF-IDF
- Used with ML models and DNN  
- Captures term importance using inverse document frequency  

### 🔤 Skip-gram Embeddings
- Used with all RNN-based models  
- Captures semantic relationships between words  

---

## 🤖 Models Implemented

### 🔹 Machine Learning Model
- Logistic Regression (TF-IDF)

### 🔹 Deep Learning Models

- Deep Neural Network (TF-IDF)  
- Simple RNN (Skip-gram)  
- GRU (Skip-gram)  
- LSTM (Skip-gram)  
- Bidirectional SimpleRNN  
- Bidirectional GRU  
- Bidirectional LSTM  

---

## ⚙️ Experimental Setup

- Total Experiments: **24 configurations**  
- Extensive hyperparameter tuning performed  
- Sequence length fixed at 100 tokens  
- Embedding dimension: 100  

Each preprocessing strategy was evaluated across all models to ensure a fair comparison.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy  
- Macro-averaged F1-score  
- Confusion Matrix  
- Classification Report  

---

## 📈 Results Summary

### 🏆 Best Overall Model (Validation)
- **TF-IDF + Logistic Regression**
- Accuracy: **94.99%**

### 🧠 Best Deep Learning Model (Test)
- **Bidirectional GRU (Skip-gram + Optimum Preprocessing)**
- Accuracy: **91.93%**
- F1-score: **91.89%**

---
📄 Project Report

A detailed academic report is included in this repository.

It contains:

Full experimental methodology
Model configurations and hyperparameters
Comparative analysis across all 24 experiments
Visualizations and performance tables
Discussion and conclusions

📌 For complete technical details, refer to the report.

---

### 🎓 Key Learning Outcomes


Through this project, the following were achieved:

- Understanding of preprocessing impact in NLP
- Comparison of feature-based vs embedding-based approaches
- Implementation of multiple RNN architectures
- Hyperparameter tuning for deep learning models
- Large-scale experimental analysis and comparison
