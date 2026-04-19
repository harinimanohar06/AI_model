## 🌐 Streamlit Translator with Cloudflare Tunnel & Groq
This repository shows how to deploy a **Streamlit app inside Google Colab**, expose it securely to the web using **Cloudflare Tunnel**, and integrate **Hugging Face** Transformers with **Groq API** for multilingual translation and accelerated inference.
---

## 📌 Project Overview
- This project demonstrates how to:
- Launch a Streamlit app directly from Colab.
- Use Cloudflare Tunnel to make the app publicly accessible.
- Load Hugging Face translation models (Helsinki-NLP/opus-mt-mul-en).
- Integrate Groq API for high-performance inference.
- Manage API tokens securely via Colab userdata.
---

## ✨ Features
- Streamlit interface for text translation
- Hugging Face model integration (AutoTokenizer, AutoModelForSeq2SeqLM)
- Groq API support for inference acceleration
- Cloudflare Tunnel for secure public access
- Token management without hardcoding secrets

---
## 🧠 Machine Learning Components
The app loads the following components:

|Component|Purpose|
|----------|---------|
|Helsinki-NLP/opus-mt-mul-en|Multilingual → English translation|
|AutoTokenizer |Tokenizes input text|
|AutoModelForSeq2SeqLM|Sequence-to-sequence translation model|
|pipeline("translation")|Hugging Face pipeline for translation|
|Groq API|Accelerated inference backend|

---
## 🛠️ Tech Stack
- Python 3.x
- Streamlit
- Hugging Face Transformers
- Groq API
- Cloudflare Tunnel
- Google Colab
---
## Project Structure
Code

├── app.py               #Streamlit app code

├── requirements.txt    # Python dependencies

└── README.md           # Project documentation

---
## References
>Hugging Face

>Groq

>Streamlit

>Cloudflare Tunnel Docs (developers.cloudflare.com in Bing)

---

## Example
Input:
Code
வணக்கம் உலகம்

---

## Output
Hello World

---

## Overview
