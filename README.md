# ESP ChatBot - AI-Powered Document Question Answering System

An intelligent chatbot that answers user queries based on the contents of uploaded PDF documents using Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG).

The system extracts text from PDF files, converts it into vector embeddings, stores them in a vector database, retrieves the most relevant information for a user's query, and generates accurate context-aware responses using an LLM.


## Features

- Upload PDF documents
- Extract text from PDFs
- Intelligent text chunking
- Generate embeddings using Hugging Face models
- Store embeddings in a vector database
- Semantic similarity search
- Context-aware question answering
- LLM-powered response generation
- Simple and scalable architecture



## Project Workflow

```
User Uploads PDF
        │
        ▼
Text Extraction
        │
        ▼
Text Chunking
        │
        ▼
Embedding Generation
        │
        ▼
Vector Database
        │
        ▼
User Question
        │
        ▼
Similarity Search
        │
        ▼
Relevant Context Retrieval
        │
        ▼
LLM Prompt
        │
        ▼
Generated Answer
```

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| Jupyter Notebook | Development Environment |
| LangChain | RAG Pipeline |
| Hugging Face Embeddings | Text Embedding |
| FAISS / Chroma (Vector Store) | Vector Database |
| Ollama LLM | Local Large Language Model |
| PyPDF | PDF Text Extraction |
| Sentence Transformers | Embedding Model |

---

## Project Structure

```
ESP-ChatBot/
│
├── espChatBot.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── PDFs
├── vectorstore/
└── images/
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/ESP-ChatBot.git

cd ESP-ChatBot
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate it

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

Open the notebook

```bash
jupyter notebook
```

Run all cells sequentially.

---

## How It Works

1. Load PDF documents.
2. Extract text from each page.
3. Split text into manageable chunks.
4. Generate embeddings.
5. Store embeddings in the vector database.
6. Accept user questions.
7. Retrieve the most relevant chunks.
8. Send retrieved context to the LLM.
9. Generate an accurate answer.

---

## Advantages

- Fast semantic document search
- Context-aware responses
- Reduces LLM hallucinations
- Works with custom PDFs
- Modular architecture
- Easy to extend
- Local LLM support

---

## Limitations

- Performance depends on document quality.
- Supports only uploaded documents.
- Large documents increase indexing time.
- Requires local model setup.

---

## Future Enhancements

- Multi-PDF support
- Chat history
- Voice interaction
- Web interface using Streamlit or Flask
- Cloud deployment
- OCR support for scanned PDFs
- Multi-language support

---

## Applications

- Educational assistants
- Technical documentation search
- Research paper analysis
- Company knowledge base
- Customer support chatbot
- Healthcare documentation
- Legal document assistant

---

## Sample Query

**Question**

```
What is ESP32?
```

**Response**

```
The chatbot retrieves the relevant content from the uploaded PDF and generates a context-aware answer using the LLM.
```

---

## Requirements

- Python 3.10+
- Jupyter Notebook
- Ollama
- LangChain
- Hugging Face
- FAISS/Chroma
- PyPDF
- Sentence Transformers

---

## Author

**Mahewish Sayyed**

B.Tech Engineering Student

Interested in Artificial Intelligence, Machine Learning, and Large Language Models.

---

## License

This project is intended for educational and learning purposes.
