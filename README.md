
# 🧠 Deep Learning Project 1: Text Generation with LSTM

This project implements a character-level Recurrent Neural Network (RNN) using **LSTM** to generate human-like text. Inspired by natural language processing techniques, the model is trained on a custom dataset of text to predict and generate coherent sequences.

---

## 📌 Project Overview

- **Goal:** Generate coherent and stylistic text using deep learning.
- **Technique:** LSTM-based character-level text generation.
- **Frameworks:** TensorFlow / Keras
- **Dataset:** Cleaned textual data (e.g., song lyrics, books, or movie scripts)

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Main programming language |
| **Jupyter Notebook** | Development & experimentation |
| **TensorFlow / Keras** | Deep learning framework |
| **Matplotlib** | Training visualization |
| **NumPy / Pandas** | Data manipulation |

---

## 🗂️ Project Structure

```bash
├── Deep Learning Project 1 (2).ipynb   # Main notebook with preprocessing, training, and generation
├── README.md                           # Project overview and documentation
├── data/                               # (Optional) Folder for input text dataset
├── models/                             # (Optional) Folder for saved model checkpoints
```

---

## 🧪 How It Works

1. **Text Preprocessing**
   - Lowercasing, character-to-index mapping
   - Sequence chunking for model input

2. **Model Architecture**
   - Embedding layer (optional)
   - One or more LSTM layers
   - Dense output layer (Softmax)

3. **Training**
   - Categorical cross-entropy loss
   - Sequence input-output pairs
   - Epochs = 20–50 depending on performance

4. **Text Generation**
   - Seed input → Predict next characters
   - Temperature scaling for creativity control

---

## 📈 Sample Results

> **Seed:** `The world is yours and`  
> **Generated:** `the dreams will light the fire of desire and turn the night into day...`

---

## 🚀 How to Run

```bash
# Step 1: Install dependencies
pip install tensorflow numpy matplotlib

# Step 2: Open Jupyter and run the notebook
jupyter notebook "Deep Learning Project 1 (2).ipynb"
```

---

## 🔮 Future Improvements

- Implement GRU and compare performance
- Add beam search or top-k sampling
- Train on larger corpora (e.g., Wikipedia, Shakespeare)
- Save and deploy model via Flask or Streamlit

---

## 👨‍💻 Author

**Manasseh Jesrun Kota**  
M.S. Business Analytics & AI @ University of Texas at Dallas  
🔗 [LinkedIn](https://www.linkedin.com/in/jesrun-kota) | 📫 jesrun@example.com *(Replace with your real one)*
