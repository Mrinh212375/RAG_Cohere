# RAG with Cohere's Command-R+ LLM.
This project facilitates conversational interactions with PDF documents through a Retrieval-Augmented Generation (RAG) model. Users can upload PDF files and ask questions based on the content, receiving detailed responses generated using RAG-based conversational techniques. The system leverages Cohere's Command R+ model for fast and efficient performance and features a Gradio interface for seamless user interactions.

Features-
1. The user can upload PDF files to interact effectively.
2. load and merge PDF files to create content for the RAG.
3. chunking of the PDFs and embedding those chunks.
4. store those chunk embeddings in vector storage for effective retrieval
5. After retrieval, rerank before feeding to LLM.
6. finally the retrieved and reranked chunks will feed into Cohere's inbuilt LLM

Frameworks used - 
1.  cohere
2.  gradio
3.  PyMuPDF
4.  langchain_community
5.  hnswlib
6.  pypdf
7.  langchain
