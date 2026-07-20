# 🤖 RAG ChatBot with n8n, Pinecone, Ollama & Gemini

An end-to-end Retrieval-Augmented Generation (RAG) chatbot workflow built with **n8n**.

This workflow automatically indexes documents from **Google Drive** into **Pinecone Vector Database** using **Ollama Embeddings**, then allows users to chat with the knowledge base using **Google Gemini**.

---

## 🚀 Features

- 📂 Automatically monitors a Google Drive folder
- 📥 Downloads newly uploaded documents
- ✂️ Splits documents into chunks
- 🧠 Generates embeddings using Ollama
- 🗄️ Stores vectors in Pinecone
- 💬 AI Chatbot powered by Google Gemini
- 🔍 Semantic search using Vector Store
- 🧠 Conversation memory
- ⚡ Fully automated with n8n

---

# 🏗 Workflow Architecture

```text
Google Drive
      │
      ▼
Google Drive Trigger
      │
      ▼
Download File
      │
      ▼
Document Loader
      │
      ▼
Text Splitter
      │
      ▼
Ollama Embeddings
      │
      ▼
Pinecone Vector Database
      │
      ▼
==============================
      Chat Interface
==============================
      │
      ▼
Google Gemini
      │
      ▼
Vector Search
      │
      ▼
AI Response
```

---

# 🛠 Tech Stack

- n8n
- Google Drive API
- Pinecone
- Ollama
- Gemini API
- Vector Search
- RAG (Retrieval-Augmented Generation)

---

# 📁 Project Structure

```
RAG1-ChatBot/
│
├── RAG1_ChatBot_Practical_GitHub_Safe.json
├── screenshots/
└── README.md
```

---

# ⚙️ Requirements

- n8n
- Pinecone Account
- Google Drive API Credentials
- Google Gemini API Key
- Ollama Installed
- nomic-embed-text model

---

# 📥 Import Workflow

1. Open n8n.
2. Click **Import Workflow**.
3. Select the JSON workflow.
4. Replace all credentials with your own.
5. Create your Pinecone Index.
6. Configure the Google Drive folder.
7. Run the workflow.

---

# 🔑 Credentials Required

- Google Drive OAuth2
- Pinecone API
- Google Gemini API
- Ollama

---

# 📸 Screenshots

> Add screenshots inside the `screenshots` folder.

Example:

- Workflow Overview
- Chat Example
- Pinecone Index
- Google Drive Folder

---

# 📌 Future Improvements

- Support multiple document formats
- Multi-user conversations
- Metadata filtering
- Hybrid Search
- Streaming responses
- Better prompt engineering

---

# 👨‍💻 Author

Hazem Z

GitHub:
https://github.com/Hazem-77

---

## ⭐ If you found this project useful, don't forget to star the repository!
