# RAG Document Q&A With Groq

A document-based Q&A app that lets you ask questions directly from your PDF research papers. It uses Groq for fast responses, OpenAI embeddings for understanding, and FAISS for efficient document search.

---

## Setup

1. Install dependencies
```bash
pip install -r requirements.txt
```

2. Create a `.env` file and add your API keys
```env
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
```

3. Add your PDF files to the `research_papers` folder

4. Run the app
```bash
streamlit run app.py
```

---

## Usage

- Click **"Document Embedding"** to load and index your PDFs
- Type your question in the input box
- Get answers based on your documents
- Expand **"Document Similarity Search"** to see the source chunks used

---

## Requirements

```
streamlit
langchain
langchain-groq
langchain-openai
langchain-community
langchain-text-splitters
faiss-cpu
pypdf
python-dotenv
```
