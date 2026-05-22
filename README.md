# Document Q&A System using RAG and Gemini AI

## What it does
Upload any PDF and ask natural language questions about it. 
The AI answers using only the content from your document.

## Architecture
- PDF Loading → PyPDFLoader
- Chunking → RecursiveCharacterTextSplitter (500 chunk size)
- Embeddings → Google Gemini (gemini-embedding-2)
- Vector Store → ChromaDB
- LLM → Google Gemini (gemini-2.5-flash)

## Setup Instructions
1. Open the notebook in Google Colab
2. Run Cell 1 to install dependencies
3. Get a free Gemini API key from https://aistudio.google.com
4. Add your API key in Cell 2
5. Upload your PDF when prompted
6. Ask questions!

## Tech Stack
- LangChain
- Google Gemini API (Free)
- ChromaDB
- PyPDF
