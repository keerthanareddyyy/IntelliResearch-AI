# 🧠 IntelliResearch-AI

> An AI-powered Research Agent built using **IBM watsonx.ai**, **IBM Granite Models**, **Langflow**, and **IBM Cloud Lite Services**.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.10%2B-brightgreen)
![IBM watsonx](https://img.shields.io/badge/IBM-watsonx.ai-blue)

---

## 📌 Overview

**IntelliResearch-AI** is an intelligent research automation agent that leverages IBM's Granite LLMs and Langflow pipelines to help users query, summarize, and synthesize research content from various sources — all via a conversational interface.

---

## 🏗️ Architecture

![Architecture Blueprint](./architecture-blueprint.png)

---

## ✨ Features

- 🔍 **AI Research Querying** — Ask complex research questions and get synthesized answers
- 📄 **Document Summarization** — Summarize research papers and articles
- 🤖 **IBM Granite LLM** — Powered by IBM's enterprise-grade Granite models
- 🔗 **Langflow Pipelines** — Visual AI pipeline orchestration
- ☁️ **IBM Cloud Lite** — Deployed on IBM Cloud (no cost tier)

---

## 🛠️ Tech Stack

| Technology | Role |
|---|---|
| IBM watsonx.ai | LLM inference & AI services |
| IBM Granite Models | Core language model |
| Langflow | Pipeline orchestration |
| IBM Cloud Lite | Cloud hosting |
| Python / Flask | Backend API |

---

## 🚀 Setup & Installation

### Prerequisites
- Python 3.10+
- IBM Cloud account (Lite tier is free)
- IBM watsonx.ai project set up

### 1. Clone the repository
```bash
git clone https://github.com/keerthanareddyyy/IntelliResearch-AI.git
cd IntelliResearch-AI
```

### 2. Create virtual environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure environment variables
```bash
cp .env.example .env
# Edit .env with your IBM credentials
```

### 5. Run the app
```bash
python app.py
```

---

## 🔑 Environment Variables

| Variable | Description |
|---|---|
| `WATSONX_API_KEY` | Your IBM Cloud API Key |
| `WATSONX_PROJECT_ID` | IBM watsonx.ai Project ID |
| `WATSONX_URL` | IBM watsonx regional endpoint |
| `GRANITE_MODEL_ID` | IBM Granite model identifier |
| `LANGFLOW_API_URL` | Langflow server URL |

---

## 👩‍💻 Developer

**A Keerthana**  
GitHub: [@keerthanareddyyy](https://github.com/keerthanareddyyy)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
