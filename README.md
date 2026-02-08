# Workspace README

This workspace contains multiple folders and files related to Retrieval-Augmented Generation (RAG), data ingestion, parsing, hybrid search strategies, query enhancement, and vector databases. Below is an overview of each folder and its contents (excluding the Langgraph folder):

## Root Files
- **main.py**: Main entry point for the project.
- **pyproject.toml**: Project configuration and dependencies.
- **README.md**: Project overview and instructions.
- **requirements.txt**: Python dependencies for the project.

## DataIngestParsing/
- **1-dataingestion.ipynb**: Notebook for ingesting various data sources.
- **2-dataparsingpdf.ipynb**: Parses PDF files for structured data extraction.
- **3-dataparsingdoc.ipynb**: Parses DOC files for extracting information.
- **4-csvexcelparsing.ipynb**: Handles CSV and Excel file parsing.
- **5-jsonparsing.ipynb**: Parses JSON files for data extraction.
- **6-databaseparsing.ipynb**: Connects to databases and parses data.
- **semantichunking.ipynb**: Implements semantic chunking of ingested data.
- **data/**: Contains sample data files for testing parsing scripts.

## hybrid_search_strategies/
- **denseparse.ipynb**: Demonstrates dense parsing for search strategies.
- **langchain_rag_dataset.txt**: Sample dataset for LangChain RAG.
- **mmr.ipynb**: Implements Maximal Marginal Relevance (MMR) search.
- **reranking.ipynb**: Shows reranking techniques for search results.

## langchainupdated/
- **main.py**: Main script for updated LangChain workflows.
- **pyproject.toml**: Project configuration for LangChain updates.
- **README.md**: Overview of LangChain updates.
- **requirements.txt**: Dependencies for LangChain updates.
- **updatedlangchain/**: Contains notebooks for various LangChain features:
    - **1-langchainintro.ipynb**: Introduction to LangChain.
    - **2-modelintegration.ipynb**: Integrating models with LangChain.
    - **3-tools.ipynb**: Using tools in LangChain.
    - **4-messages.ipynb**: Handling messages in LangChain.
    - **5-structuredoutput.ipynb**: Structured output generation.
    - **6-middleware.ipynb**: Middleware integration.


## QueryEnhancement/
- **HyDE.ipynb**: Implements Hypothetical Document Embeddings (HyDE).
- **langchain_crewai_dataset.txt**: Dataset for CrewAI and LangChain.
- **querydecomposition.ipynb**: Decomposes queries for improved search.
- **queryexpansion.ipynb**: Expands queries for better retrieval.
- **output/**: Stores output files from query enhancement experiments.

## VectorDatabases/
- **1-chromadb.ipynb**: Introduction and usage of ChromaDB.
- **2-faiss.ipynb**: FAISS vector database usage.
- **3-Othervectorstores.ipynb**: Other vector store implementations.
- **Datastaxdb+%281%29.ipynb**: Datastax database integration.
- **doc_0.txt, doc_1.txt, doc_2.txt**: Sample documents for vector database experiments.
- **embedding.ipynb**: Embedding generation for vector databases.
- **openaiembeddings.ipynb**: Using OpenAI embeddings.
- **PineconeVectorDB.ipynb**: Pinecone vector database usage.

---

For detailed descriptions, refer to the individual notebook files. Each notebook contains code and explanations for its specific topic.

