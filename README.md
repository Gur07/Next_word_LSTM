
````markdown
# 📝 Next Word Predictor using LSTM on Shakespeare's *Hamlet*

This project implements a deep learning model to predict the next word in a given sequence of words, trained on the text from Shakespeare’s famous play **"Hamlet"**. The model uses **LSTM (Long Short-Term Memory)** networks, which are powerful for sequence modeling tasks like text prediction.

---

## 📚 Dataset
- **Source:** *Hamlet* by William Shakespeare
- The dataset provides a rich vocabulary and complex sentence structures, making it ideal for language modeling.

---

## 🔧 Tech Stack & Tools

- **Python 3**
- **TensorFlow / Keras** – for building the LSTM model
- **NumPy, Pandas** – for data handling
- **Streamlit** – for building the interactive web app
- **Pickle** – for saving and loading the tokenizer
- **Hamlet text corpus** as the dataset

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Text tokenization
- Sequence generation
- Padding sequences to uniform lengths
- Splitting into training and validation sets

---

### 2️⃣ Model Architecture
- **Embedding Layer** – to map words into dense vector space
- **Two LSTM Layers** – to capture temporal dependencies in text
- **Dense Softmax Output Layer** – to predict the next word from the vocabulary

---

### 3️⃣ Training
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  
- **Early Stopping** implemented to monitor validation loss and prevent overfitting

---

### 4️⃣ Evaluation
- Evaluated using sample inputs to manually verify predicted next words
- Checked for logical correctness in word predictions

---

### 5️⃣ Deployment
- Deployed using **Streamlit**: Users can input a sentence and get the next word prediction instantly via a web interface.

---

## 🚀 Running the App

```bash
pip install streamlit tensorflow numpy pickle-mixin
streamlit run app.py
````

---

## 💡 Example

**Input:**
`To be or not to`

**Predicted Next Word:**
`be`

---

## 📝 Learnings

* Built LSTM-based next word prediction models.
* Managed text sequences and padding effectively.
* Deployed an interactive NLP model using Streamlit.
* Saved and loaded Tokenizer objects via Pickle.

---

## 🎯 Future Work

* Expand training dataset to modern corpora.
* Experiment with GRUs, Transformers, and GPT models.
* Improve model generalization for broader language use.

---

## 📌 Applications

* Text Autocomplete Systems (e.g., Google Suggest)
* AI Writing Assistants
* Chatbots & Conversational AI

---

## 🤝 Contributions

Open to ideas, improvements, and collaborations!

```

