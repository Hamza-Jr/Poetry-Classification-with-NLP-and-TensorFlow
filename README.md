# **Poem Genre Classification using NLP and LSTM**

### **📌 Project Overview**
This project applies **Natural Language Processing (NLP)** and **Deep Learning** techniques to classify poems into different genres. Using **LSTM (Long Short-Term Memory) networks**, we process and analyze poetic texts to automatically identify their categories.

---

## **📂 Table of Contents**
- [ Introduction](#-introduction)
- [ Dataset](#-dataset)
- [ Dependencies](#-dependencies)
- [ Preprocessing](#-preprocessing)
- [ Model Architecture](#-model-architecture)
- [ Training and Evaluation](#-training-and-evaluation)

---

## ** Introduction**
This NLP-based project classifies poems into genres using **LSTM networks**. The process involves:
- **Text Preprocessing**: Stopword removal, tokenization, and padding sequences.
- **Word Embeddings**: Words converted into dense vector representations.
- **Deep Learning Model**: LSTM layers for text sequence learning.

The model is trained using **TensorFlow and Keras**, providing accurate classification for poetic genres.

---

## ** Dataset**
The dataset contains labeled poems categorized into various genres. The key datasets used are:
- **Training Dataset**: `Poem_classification - train_data.csv`
- **Test Dataset**: `Poem_classification - test_data.csv`

Each dataset contains:
- **Poem**: The text of the poem.
- **Genre**: The corresponding category of the poem.

---

## ** Dependencies**
Install the required libraries before running the project:

bash
pip install pandas numpy nltk tensorflow scikit-learn


## ** preprocessing**
The text data is preprocessed with the following steps:

-Lowercasing the text.
-**Removing punctuation and extra spaces.**
-**Removing stopwords using nltk.**
-**Tokenizing the text into word sequences.**
-**Padding sequences to a uniform length.**

---

## ** Model Architectures**
The LSTM-based model consists of:

-**Embedding Layer**: Converts words into dense vector representations.
-**LSTM Layers**: Capture sequential dependencies in the text.
-**Dropout Layer**: Reduces overfitting.
-**Dense Layers**: Fully connected layers for classification.
-**Output Layer**: Uses a Softmax activation function for multi-class classification.

---

## ** Training and Evaluation**

Training Configuration
- **Optimizer **: Adam
-**Loss Function**: Sparse Categorical Crossentropy
-**Metrics**: Accuracy
-**Batch Size**: 32
-**Epochs**: 5










---

