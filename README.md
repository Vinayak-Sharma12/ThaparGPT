# **Title: ThaparGPT**


 ## **1. Description**
  This project, ThaparGPT, is a Streamlit-based application designed to answer questions related to Thapar University.It leverages LangChain's capabilities, combining FAISS for vector storage and retrieval, HuggingFaceEmbeddings for embedding generation, and Cohere for language modeling.
  ThaparGPT is a RAG (Retrieval-Augmented Generation)-based application. This means it combines two powerful techniques:

Retrieval: The app first retrieves relevant information from a large text corpus. It uses a FAISS index to store text chunks as dense vector embeddings, which allows it to quickly identify and retrieve the most relevant pieces of text in response to a user's query.

Augmented Generation: After retrieving the relevant text, ThaparGPT uses Cohere's language model to generate a precise answer. The model takes the retrieved context into account, ensuring that the answer is both relevant and accurate.ThaparGPT is a RAG (Retrieval-Augmented Generation)-based application. This means it combines two powerful techniques:

Retrieval: The app first retrieves relevant information from a large text corpus. It uses a FAISS index to store text chunks as dense vector embeddings, which allows it to quickly identify and retrieve the most relevant pieces of text in response to a user's query.

Augmented Generation: After retrieving the relevant text, ThaparGPT uses Cohere's language model to generate a precise answer. The model takes the retrieved context into account, ensuring that the answer is both relevant and accurate.

## **2. Methodology**

  ### **Indexing**
  <img src="https://python.langchain.com/v0.1/assets/images/rag_indexing-8160f90a90a33253d0154659cf7d453f.png" width="80%" height="80%">

  ### **Retrieval and Generation**
  <img src="https://python.langchain.com/v0.1/assets/images/rag_retrieval_generation-1046a4668d6bb08786ef73c56d4f228a.png" width="80%" height="80%">

## **3. Input / Output**
<img src="https://i.postimg.cc/vBz1tfQN/Screenshot-2024-08-13-at-5-30-56-PM.png" width="40%" height="40%">
