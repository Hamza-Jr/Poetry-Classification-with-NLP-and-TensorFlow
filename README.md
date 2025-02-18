# **Poetry Classification with NLP and TensorFlow**

### **Project Overview**
This project aims to classify poems into different **literary genres** using **Natural Language Processing (NLP)** and **deep learning**. The model is trained on a dataset of poems, utilizing **word embeddings**, **sequence models**, and **text classification techniques** to achieve accurate categorization.

---

## **📌 Table of Contents**
- [📖 Introduction](#-introduction)
- [📂 Datasets](#-datasets)
- [⚙️ Dependencies](#-dependencies)
- [🧠 Model Architecture](#-model-architecture)
- [📊 Training and Evaluation](#-training-and-evaluatio
- n)
- [🎯 Results](#-results)
- [🚀 Future Enhancements](#-future-enhancements)
- [▶️ How to Run](#-how-to-run)

---

## **📖 Introduction**
This project classifies poetry into different genres such as:
- **Romance**
- **Nature**
- **Sadness**
- **Motivation**
- **Philosophy**

The system leverages NLP techniques like **TF-IDF vectorization**, **word embeddings**, and **RNN/LSTM models** for efficient text classification. The model is built using **TensorFlow and Keras**, incorporating preprocessing steps like **stopword removal, lemmatization, and tokenization**.

---

## **📂 Datasets**
The dataset consists of poems collected from various sources and structured into labeled text samples.

1. **Kaggle Poetry Dataset**  
   - Contains thousands of poems categorized by themes and authors.  
   - 🔗 [Dataset Link](https://www.kaggle.com/datasets)

---

## **⚙️ Dependencies**
To run this project, install the following libraries:

```bash
pip install tensorflow keras numpy pandas nltk scikit-learn matplotlib
