# CodeAssistFlow – Intent-Aware AI Coding Assistant

## 📌 Overview
**CodeAssistFlow** is a Python-based AI assistant pipeline designed to understand user intent and provide relevant code assistance.  
It combines **intent classification**, **example retrieval**, and **large language model (LLM) generation** to produce accurate and context-aware outputs.

This project uses a **lightweight Retrieval-Augmented Generation (RAG)-style approach**:
- Retrieves relevant code snippets from an internal example bank based on user intent.
- Feeds the retrieved examples along with the user query into an LLM for response generation.

## 📂 Features
- Intent classification (code generation, code explanation, unknown)
- Retrieval of relevant examples for context injection
- Code generation or explanation using **DeepSeek-Coder** LLM
- Modular design with **LangGraph** for process orchestration

## ⚙️ Requirements
Python 3.8+ recommended.

Install dependencies:
```bash
pip install -r requirements.txt
```

## 🚀 Usage
1. Clone this repository:
```bash
git clone https://github.com/AhmedAlaa30/CodeAssistFlow.git
cd CodeAssistFlow
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter Notebook:
```bash
jupyter notebook CodeAssistFlow.ipynb
```

## 🛠️ Tools & Libraries
- Python
- LangGraph
- Transformers (Hugging Face)
- PyTorch

## 📜 License
MIT License
