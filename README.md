# 🎓 Student Assistant Bot with RAG 📚

A powerful AI-powered Student Assistant Bot that leverages **RAG (Retrieval-Augmented Generation)** to answer student queries with document-grounded responses. Designed to integrate seamlessly with educational content and provide reliable, contextual answers!

---

## 🚀 Features

- 📄 **Document-based Query Understanding**  
  Retrieves information from PDFs, notes, or course materials.

- 🧠 **LLM-Powered Reasoning**  
  Combines document retrieval with language model understanding using Retrieval-Augmented Generation.

- 🎯 **Accurate and Contextual**  
  Provides source-backed answers to improve trust and accuracy.

---

## 📦 Tech Stack

| Component           | Tech Used                       |
|-------------------- |----------------------------------|
| 💬 LLM             | OpenAI / OpenRouter               |
| 📚 RAG Upload      | Qdrant / docling                  |
| 🗂️ Document Loader | Docling / Embedding Models       |
| ⚙️ Backend         | Python                           |
| 🌐 Frontend        | Streamlit                        |

---

## 🧠 How It Works

1. **Ingest Documents**  
   Academic materials (PDFs, text, etc.) are split into chunks and indexed.

2. **User Asks a Question**  
   The bot receives a student query (e.g., "What is deadlock in OS?").

3. **Retriever Finds Relevant Chunks**  
   The retriever scans vectorized content to fetch top-matching passages.

4. **Generator Forms the Answer**  
   The LLM reads the relevant chunks and generates a precise, helpful answer.

---

## 🛠️ Setup Instructions

### 1. 🔧 Install Dependencies

```bash
pip install -r requirements.txt
