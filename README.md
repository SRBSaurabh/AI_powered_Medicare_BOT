# Medicare_BOT: Your AI-Powered Medical Chat Assistant

Welcome to **Medicare_BOT**, your intelligent AI-powered chatbot designed to assist with medical queries, symptom analysis, and general healthcare guidance. 🚑💡

---

## 🏥 How It Works
This bot is trained on all the **medical books** provided in the `data` folder. 
You can ask any question related to **medicine, diseases, symptoms, and treatments**, and it will provide **grounded & accurate responses** instead of random hallucinations. Each response is backed by proper **document references**, ensuring reliability and trustworthiness. 🏥📚

---
## 🚀 Getting Started

To set up and run **Medicare_BOT**, follow the steps below. This guide assumes you have **Pipenv** installed. If not, check out the official Pipenv installation guide:
[Install Pipenv](https://pipenv.pypa.io/en/latest/installation.html)

---
## 🔧 Environment Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Medicare_BOT.git
cd Medicare_BOT
```

### 2️⃣ Install Dependencies
Run the following commands to set up the virtual environment and install required packages:
```bash
pipenv install
pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub streamlit
```

### 3️⃣ Activate Virtual Environment
```bash
pipenv shell
```

### 4️⃣ Run the Chatbot
```bash
streamlit run app.py
```

---
## 🔍 Features
✅ **AI-Powered Chat** – Get quick and intelligent responses to medical queries.  
✅ **Symptom Analysis** – Input symptoms and receive potential condition insights.  
✅ **Secure & Private** – No sensitive data storage; user privacy is a priority.  
✅ **Powered by LangChain & Hugging Face** – Ensuring cutting-edge NLP capabilities.  

---