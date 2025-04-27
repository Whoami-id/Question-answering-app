# 📚 Chat with Documents App (LangChain + OpenAI + Streamlit)

This is a full stack app that lets you **upload a document (PDF, DOCX, TXT)** and **ask questions** about it using a **Large Language Model (LLM)**!

It uses:
- [LangChain](https://langchain.dev/) for document processing
- [OpenAI](https://platform.openai.com/) for LLM and Embeddings
- [ChromaDB](https://docs.trychroma.com/) as a local vector database
- [Streamlit](https://streamlit.io/) for the web frontend

---

## 🚀 Features

- ✅ Upload **PDF**, **DOCX**, or **TXT** files
- ✅ Automatic chunking of large documents
- ✅ Embedding generation via **OpenAI Embeddings API**
- ✅ Store document vectors locally with **ChromaDB**
- ✅ Query document content using **semantic search + GPT**
- ✅ Display conversation history inside the app
- ✅ Super lightweight and easy to run!

---

## 🛠 Installation

### 2. Install required packages

```bash
pip install -r requirements.txt
```

### 3. Add your OpenAI API Key

Create a `.env` file:

```bash
OPENAI_API_KEY=your-openai-key-here
```

---

## 🖥️ Usage

Start the Streamlit app:

```bash
streamlit run chat_with_documents.py
```

Then upload a document and start chatting with it in your browser!

---

## 📦 How It Works

| Step                  | Purpose                                          |
|------------------------|--------------------------------------------------|
| Upload Document        | PDF, DOCX, TXT support                           |
| Chunking               | Breaks content into manageable pieces            |
| Embedding              | Creates vector representations of chunks         |
| Vector Store           | Saves chunks in ChromaDB for fast retrieval       |
| Query                  | Matches user question to relevant chunks         |
| Answer                 | Feeds context to GPT for generating responses    |
| Chat History           | Maintains a log of conversation in session       |

---

## 🧩 Project Structure

| File                     | Purpose                        |
|---------------------------|--------------------------------|
| `chat_with_documents.py`  | Main Streamlit app             |
| `requirements.txt`        | Python dependencies            |
| `.env`                    | Your API keys                  |
| `README.md`               | Project documentation          |

---

