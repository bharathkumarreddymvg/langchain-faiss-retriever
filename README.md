# 🔎 LangChain FAISS Search

An **AI-powered semantic search engine** built using **LangChain** and **FAISS** for fast, intelligent information retrieval from multiple data sources like **Wikipedia** and **arXiv**.  
This project demonstrates how to combine LLM-based query understanding with vector similarity search to deliver relevant and context-aware results.

---

## 🚀 Features

- ⚡ **FAISS Vector Store Integration** – Enables efficient semantic search using embeddings.  
- 📚 **Multi-Source Knowledge Retrieval** – Searches both Wikipedia and arXiv for accurate, research-driven results.  
- 🧠 **LangChain Framework** – Powers the orchestration of search tools and embedding pipelines.  
- 🔍 **Natural Language Query Support** – Input queries in plain English; get summarized results.  
- 🧩 **Easily Extensible** – Add new data sources or models with minimal code changes.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Framework | LangChain |
| Vector DB | FAISS |
| Data Sources | Wikipedia, arXiv |
| Language | Python 3.10+ |
| Optional Tools | Gradio / Streamlit (for UI) |

---

## ⚙️ Installation

### 1. Clone this repository
```bash
git clone https://github.com/<your-username>/langchain-faiss-search.git
cd langchain-faiss-search

2. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

```

▶️ Usage

Run the notebook:

jupyter notebook search-engine.ipynb

📊 Project Workflow

Query Input → User enters a natural language question

Data Retrieval → Wikipedia & arXiv queried for relevant text

Embedding Creation → Results converted into vector embeddings

FAISS Indexing → Stored for efficient similarity search

Semantic Match → Retrieves contextually closest results

Result Display → Outputs relevant summaries or abstracts

