# 🤖 Conversational RAG with PDF and Chat History

This project is a **Streamlit-based Conversational Retrieval-Augmented Generation (RAG)** app that allows users to **upload PDFs** and **ask questions** about their contents using **Groq LLMs** (like Gemma-2b/9b). It supports **session-based chat history**, allowing for more natural conversations grounded in context.

---

## 🚀 Features

- 📄 Upload one or more PDF files
- 🧠 Automatically chunk and embed text using HuggingFace embeddings
- 🔎 Perform retrieval from embedded document chunks via ChromaDB
- 💬 Ask context-aware questions (using Groq's LLM + LangChain)
- 🧵 Maintains **session-specific chat history** for better conversations

---

## 🛠️ Tech Stack

- **Frontend/UI**: [Streamlit](https://streamlit.io/)
- **LLM**: [Groq API (Gemma 2b/9b)](https://console.groq.com/)
- **Embeddings**: [HuggingFace Transformers](https://huggingface.co/)
- **Vector DB**: [Chroma](https://www.trychroma.com/)
- **Framework**: [LangChain](https://www.langchain.com/)
