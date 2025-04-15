# 🤖 Chatbot with TensorFlow, NLTK & Python

This project is a simple AI-powered chatbot built with Python, NLTK (Natural Language Toolkit), and TensorFlow. It uses basic NLP techniques and a neural network classifier to understand and respond to user inputs based on intent classification.

---

## 📌 Features

- 🧠 Intent recognition using bag-of-words and lemmatization
- 🗂 Custom `intents.json` dataset for training
- 🏗 Built using TensorFlow's Sequential model
- 💬 Interactive GUI built with Tkinter
- 🧾 Words and classes stored with `pickle` for inference
- 🔁 Easily extensible with new intents and responses

---

## 📂 Project Structure
chatbot/ │ 
  ├── chatbot-python-project-data-codes/ │ 
          ├── train_chatbot.py # Trains the model │ 
                  ├── chatgui.py # Tkinter-based chatbot interface │ 
                  ├── intents.json # Custom intents dataset │ 
                  ├── words.pkl # Pickled vocabulary │ 
                  ├── classes.pkl # Pickled intent labels │ 
                  └── chatbot_model.h5 # Trained model │ 
                  ├── .gitignore 
├── requirements.txt '
└── README.md


---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7+
- `pip` (Python package manager)

---

### 📦 Installation

```bash
# Clone the repository
git clone https://github.com/IndudharAdi/chatbot-tensorflow-nlp.git
cd chatbot-tensorflow-nlp

# (Optional) Create virtual environment
python -m venv venv
venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt
```
### Train the Chatbot Model
python chatbot-python-project-data-codes/train_chatbot.py

### Run the Chatbot GUI
python chatbot-python-project-data-codes/chatgui.py

###  Built With
Python

TensorFlow/Keras

NLTK

Tkinter


