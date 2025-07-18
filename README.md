# 🧠 Intellipaper - AI Research Paper Summarizer

SummarAIze is an AI-powered web application built with **Streamlit** that summarizes academic research papers into concise, easy-to-read summaries. Just upload your `.pdf` file and get a readable summary in seconds — perfect for researchers, students, and professionals who want to save time.

link of google colab ->  https://colab.research.google.com/drive/1qivgnCT-51Q82RcBOwrCB0CV4ZkLNaiI?usp=sharing

---

## 🚀 Features

- 📄 Upload research paper (PDF)
- ⚡ Fast and accurate summarization using HuggingFace Transformers
- 🧠 Pre-trained NLP model for extractive/abstractive summarization
- 🖥️ Clean and interactive Streamlit GUI
- 💬 Output summary is copyable and readable

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?&logo=Streamlit&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗-Transformers-orange)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-PDF%20Parsing-blue)

---


## 📦 Installation

### 🔁 Clone the Repository

```bash
git clone https://github.com/your-username/summarAIze.git
cd summarAIze
```
📥 Install Dependencies
```bash
pip install -r requirements.txt
⚠️ If you face issues with keras or transformers, use:
```
```bash
pip uninstall keras
pip install tf-keras
▶️ Usage
💻 Local Run
```
```bash
streamlit run summarizer.py
```

📁 Project Structure
```bash
summarAIze/
│
├── summarizer.py        # Main Streamlit app
└── sample.pdf           # Example paper
```
```
📄 Example Models Used
facebook/bart-large-cnn (via 🤗 Hugging Face)
```

Supports other summarization models as well

