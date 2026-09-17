# 📄 RAG Document Chatbot

A Retrieval-Augmented Generation (RAG) based document chatbot built using Python and Streamlit.

## 🚀 Features

- Upload PDF documents
- Extract text from PDF
- Split documents into chunks
- Generate document embeddings
- Store embeddings using FAISS
- Retrieve relevant document content
- Ask questions about uploaded documents
- Generate answers using Groq LLM
- Chat-based Streamlit interface

## 🛠️ Technologies Used

- Python
- Streamlit
- PyPDF
- Sentence Transformers
- FAISS
- Groq API
- python-dotenv

## 🔄 How It Works

1. User uploads a PDF.
2. Text is extracted from the document.
3. The document is divided into smaller chunks.
4. Embeddings are generated using Sentence Transformers.
5. FAISS stores and searches the embeddings.
6. Relevant chunks are retrieved based on the user's question.
7. Groq LLM generates the final answer using the retrieved context.

## 📸 Project Screenshot

![Project Screenshot](screenshots/project-screenshot.png)

## ⚙️ Installation

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd rag-document-chatbot
pip install -r requirements.txt


## 👨‍💻 Author

**Shajahan M**

AI/ML Engineer 