# DocuChat

<img src="https://github.com/user-attachments/assets/c5899b97-4548-46f3-a460-1457fcff4faa" alt="image" width="700" />

This project is a **Streamlit-based web application** that allows users to upload a document (PDF, DOCX, or TXT) and interact with its contents through a conversational interface. The app leverages **LangChain**, **OpenAI GPT-3.5-turbo**, and **Chroma** for document processing and conversational retrieval.

---

## Features
- **File Upload**: Supports PDF, DOCX, and TXT files.
- **Document Processing**:
  - Reads the uploaded document.
  - Splits it into smaller chunks for better context handling.
  - Generates embeddings using OpenAI's embedding model.
- **Conversational Interface**:
  - Allows users to ask questions about the uploaded document.
  - Provides responses based on relevant document chunks retrieved using embeddings.
  - Maintains a chat history for context continuity.
- **Conversational Retrieval**:
  - Combines the power of a retriever and GPT-3.5-turbo for accurate answers.

---

## Technology Stack
- **Streamlit**: For creating the web interface.
- **LangChain**: For document handling, text splitting, and conversational retrieval.
- **OpenAI GPT-3.5-turbo**: For natural language understanding and response generation.
- **Chroma**: Vector store for efficient document chunk retrieval.
