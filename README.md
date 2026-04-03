# 📌 Next Word Prediction using RNN (TensorFlow)
## 📖 Overview

This project is a Natural Language Processing (NLP) application that predicts the next word in a sequence using a Recurrent Neural Network (RNN).

The model is trained on a sample text and learns word patterns to generate meaningful text, similar to autocomplete systems.

## 🚀 Features
- Text preprocessing and tokenization
- N-gram sequence generation
- Sequence padding
- RNN-based deep learning model
- Next-word prediction function
- Text generation capability

## 🛠️ Tech Stack
Python 
TensorFlow
NumPy
NLP (Tokenization, Sequence Modeling)

## 📂 Project Workflow
1️⃣ Text Preprocessing
Convert text to lowercase
Tokenize words using Keras Tokenizer
2️⃣ Sequence Generation
Create n-gram sequences from text
3️⃣ Padding
Pad sequences to equal length using pad_sequences
4️⃣ Feature & Label Creation
Input (X): sequence of words
Output (y): next word
5️⃣ Model Building
Embedding Layer → Word vector representation
SimpleRNN Layer → Sequence learning
Dense Layer (Softmax) → Next word prediction
6️⃣ Training
Loss: Categorical Crossentropy
Optimizer: Adam
Epochs: 100
7️⃣ Prediction
Generates next words based on input seed text
## 🧠 Model Architecture
Embedding Layer → SimpleRNN → Dense (Softmax)

## 🔥 Future Improvements
- Replace SimpleRNN with LSTM / GRU
- Use larger datasets
- Add dropout for regularization
- Use pretrained embeddings (GloVe, Word2Vec)
- Implement Transformer-based models (BERT/GPT)

## 🎯 Applications
- Text autocomplete
- Chatbots
- AI writing assistants
- Search engines
