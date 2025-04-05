# 🧠 Agentic RAG-Based Medical Assistant using Gemini + FAISS + LangChain

A powerful Retrieval-Augmented Generation (RAG) system with agentic AI tools designed for **evidence-based clinical decision support**. This project integrates:

- **📚 FAISS** for fast vector similarity search over medical literature
- **🧠 Gemini (gemini-1.5-flash)** for advanced generative responses
- **🤖 LangChain Agents** for tool-augmented reasoning

---

## 🔍 Features

- ✅ Retrieve the most relevant medical documents using vector search
- ✅ Analyze symptoms and suggest potential diagnoses
- ✅ Recommend treatment plans based on retrieved evidence
- ✅ Agent-based decision-making with structured reasoning

---

## 📁 Project Structure

```bash
.
├── medical_literature.txt       # Your custom medical documents (knowledge base)
├── faiss_index/                 # Saved FAISS vector store and metadata
├── main.py                      # Full agent-based RAG pipeline
├── README.md                    # This documentation
