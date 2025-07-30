# 🛡️ Cybersecurity PDF Chatbot using Retrieval-Augmented Generation (RAG)

This project is a domain-specific Retrieval-Augmented Generation (RAG) chatbot focused on **Cybersecurity**. It enables users to upload cybersecurity documents (whitepapers, policies, threat intelligence reports, etc.) and interact with them via natural language questions using an AI model.

---

## 🔐 Use Case

> Need quick answers from a 100-page NIST PDF? Want to summarize the latest threat intelligence? Just upload, ask, and get accurate answers.

---

## 🧠 Key Features

- 📄 PDF Ingestion: Upload and parse cybersecurity PDFs.
- 🧠 RAG Pipeline: Combines dense retrieval with language generation for contextual answers.
- 🧾 Document Embedding: Uses domain-adapted sentence transformers.
- ⚡ FAISS Indexing: Fast similarity search over embedded chunks.
- 💬 Gradio Chat UI: Chatbot interface to interact with your documents.
- 🔐 Secure API Access: Integrates with Hugging Face models using API key.

---

## 🛠️ Installation

### Step 1: Clone the Repo

```bash
git clone https://github.com/your-org/cyber-rag-chatbot.git
cd cyber-rag-chatbot
