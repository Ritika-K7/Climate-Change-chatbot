# 🌍 Climate Change Chatbot

An intelligent chatbot that helps users explore and understand climate change using the **IPCC Report** as its knowledge base. It combines modern AI techniques with a user-friendly web interface to deliver both accurate and understandable answers.

---

## 📌 Features

- Ask natural language questions about climate change
- Retrieves factual content from the IPCC report
- Displays both raw source data and GPT-generated answers
- Fully interactive web app powered by **Streamlit**

---

## 🧠 Tech Stack

| Component | Technology |
|----------|------------|
| Programming Language | Python |
| Web Interface | Streamlit |
| Vector Database | ChromaDB |
| LLM | OpenAI GPT-3.5 Turbo |
| Semantic Search | RAG (Retrieval-Augmented Generation) |
| PDF Processing | PyPDF |

---

## ⚙️ How It Works

1. **User Input**: A user types a question into the Streamlit interface.
2. **Document Retrieval**:
   - The IPCC report is indexed into **ChromaDB** as vector embeddings.
   - Relevant passages are fetched using semantic search.
3. **Answer Generation**
