# 🧠 Next Word Prediction Using LSTM with Streamlit

This is a Streamlit web application that predicts the **next word** in a given sentence using a trained **LSTM (Long Short-Term Memory)** model in TensorFlow/Keras. It utilizes a tokenizer for encoding text and demonstrates the power of deep learning in language modeling.

## 🚀 Demo

> _"To be or not to"_ → **Predicts:** _"be"_

## 📦 Features

- LSTM model trained for next-word prediction
- Uses early stopping for efficient training
- Streamlit interface for interactive use
- Tokenizer-based input preprocessing
- Uses Keras `pad_sequences` for uniform input shape

---

## 🛠️ Project Structure

- app.py # Streamlit app script
- next_word_lstm.h5 # Trained LSTM model file
- tokenizer.pickle # Tokenizer used during training
- requirements.txt # Python dependencies
- README.md # Project documentation