# AI-Powered-Agent-with-RAG-and-Langchain

### Overview

This project implements an AI-powered agent using Retrieval-Augmented Generation (RAG) to provide intelligent responses by leveraging document retrieval, web scraping, and conversational memory. The system integrates multiple data sources such as PDFs, text files, web data, and databases (planned for future implementation).

### Features

**Retrieval-Augmented Generation (RAG):** Utilizes FAISS for efficient document retrieval.

**Web Scraping:** Extracts content from various online sources.

**PDF and Text File Processing:** Supports parsing and indexing of documents.

**Google Search Integration:** Leverages Google API for external search queries.

**Conversational Memory:** Maintains context across multiple queries.

**Extensibility:** Future support for local repositories and databases.

### Tools and Technologies

**Programming Language:** Python

**Frameworks & Libraries:**

LangChain

HuggingFace Embeddings

FAISS (Facebook AI Similarity Search)

BeautifulSoup (Web Scraping)

Requests (HTTP Requests)

**LLMs Used:**

Groq Llama3-8b-8192

HuggingFaceHub models

**APIs Used:**

Google Custom Search API

Google Serper API

**Memory Management:**

ConversationBufferWindowMemory


### Setup Instructions

**Clone the Repository:**

    git clone https://github.com/Bakhshial/AI-Powered-Agent-with-RAG-and-Langchain.git
    cd ai-agent-rag

**Install Dependencies:**

    pip install -r requirements.txt

**Configure API Keys:**

    Add your API keys to environment variables in Google Colab or .env file.
    export GROQ_API_KEY=your_groq_api_key
    export SERPER_API_KEY=your_serper_api_k

### Usage

**PDF Question Answering:**
Upload PDFs and query insights from them.

**Web-Based Information Retrieval:**
Query real-time information from web sources.

**Google Search:** Search anything from google

**Conversational AI:**
Engage in context-aware conversations with memory.

### Future Work

**Enhanced Database Integration:**
Future versions will support integration with relational and NoSQL databases.

**Multi-modal Data Processing:**
Expanding capabilities to include image and audio data analysis.

**Improved Model Fine-tuning:**
Implementing fine-tuned models for domain-specific queries.

**Web Interface:** Create interface for future easy access

### Contribution

We welcome contributions! To contribute:

Fork the repository.

Create a new branch for your feature.

Commit your changes and push to your fork.

Open a pull request.

### License

This project is licensed under the Apache License 2.0.
