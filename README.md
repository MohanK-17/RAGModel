# 🧠 Build Local AI Agents with Python

> Run your own intelligent agents — completely local and free!

This project demonstrates how to build powerful local AI agents using:
- 🦙 **Ollama** for running LLMs locally  
- 🔗 **LangChain** for building agent pipelines  
- 📚 **ChromaDB** for local vector storage and semantic search  

Everything runs **locally** — no cloud or API keys needed!

---

## 🚀 Features

- Run LLMs on your own machine (e.g., LLaMA 3, Mistral, etc.)
- Use vector databases for context-aware retrieval
- Build intelligent agents with memory and tool use
- 100% local: private, secure, and offline-capable

---

## 🛠️ Tech Stack

| Tool        | Role                              |
|-------------|-----------------------------------|
| **Ollama**  | Runs local LLMs (e.g., LLaMA3)    |
| **LangChain** | Framework for building LLM-powered agents |
| **ChromaDB** | Local vector database for semantic search |

---

## 📦 Installation

1. **Clone the repo**
```bash
git clone https://github.com/your-username/Sriram2226-rag-qasystem.git
cd RAGModel
```
2. **Create and activate a virtual environment**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

This will install all necessary libraries.


## OLLAMA Setup (Locally)

1. **Download Ollama**
```bash
https://ollama.com/
```
2. **Check it downloaded correctly**

Open Terminal
```bash
ollama
```
3.**Pull llama3.2**
```bash
ollama pull llama3.2
```
4.**pull a embeding model**
```bash
ollama pull maxbai-embed-large
```
## Run The Model
```bash
python main.py
```