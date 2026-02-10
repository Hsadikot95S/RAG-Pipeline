## Autonomous_Rag/
Contains advanced RAG strategies and experiments:
 - **3-COTRag.ipynb**: Chain-of-Thought RAG experiments.
 - **4-Selfreflection.ipynb**: Self-reflection in RAG pipelines.
 - **5-QueryPlanningdecomposition.ipynb**: Query planning and decomposition for RAG.
 - **6-Iterativeretrieval.ipynb**: Iterative retrieval strategies.
 - **7-answersynthesis.ipynb**: Answer synthesis techniques for RAG.

## RAG_Agents/
Contains agent-based RAG experiments and debugging:
 - **1-streaming.ipynb**: Streaming agent RAG.
 - **3-Debugging/**: Debugging utilities and notebooks for RAG agents.
 - **7-ReActAgents.ipynb**: ReAct agent-based RAG.

## React_Agents/
Agentic and ReAct-based RAG experiments:
 - **1-AgenticRAG-2.ipynb**: Agentic RAG experiments (version 2).
 - **1-agenticrag.ipynb**: Agentic RAG experiments.
 - **1-streaming.ipynb**: Streaming agent RAG.
 - **2-ReAct.ipynb**: ReAct agent experiments.
 - **7-ReActAgents.ipynb**: ReAct agent-based RAG.
 - **research_notes.txt**: Research notes for agentic RAG.
 - **sample_docs.txt**: Sample documents for agentic RAG.

## Top-level Notebooks and Files
- **1-rag_evaluation.ipynb**: Evaluation of RAG pipelines and strategies.
- **2-CorrectiveRAG.ipynb**: Corrective RAG techniques and experiments.
- **4-AdaptiveRAG.ipynb**: Adaptive RAG strategies.
- **8-multiagent.ipynb**: Multi-agent RAG experiments.
- **cache_augment_generation.ipynb**: Caching and augmentation in RAG generation.
- **cache_augment_generration.ipynb**: (Possible duplicate or variant; check for correct spelling and content.)
- **rag_evaluation.ipynb**: (Possible duplicate or variant; check for correct spelling and content.)
- **CorrectiveRAG.ipynb**: (Possible duplicate or variant; check for correct spelling and content.)
- **AdaptiveRAG.ipynb**: (Possible duplicate or variant; check for correct spelling and content.)
- **ragmemory.ipynb**: Memory-augmented RAG experiments.
- **uv.lock**: Lock file for dependency management.
- **.env**: Environment variables (excluded from version control).
- **.gitignore**: Git ignore rules for sensitive and build files.
- **.python-version**: Python version specification.
- **.secrets.baseline**: Security baseline for secrets scanning.
- **.venv/**: Python virtual environment directory.
# Workspace README

This workspace contains multiple folders and files related to Retrieval-Augmented Generation (RAG), data ingestion, parsing, hybrid search strategies, query enhancement, vector databases, LangGraph, and a full RAG pipeline. Below is an overview of each folder and its contents:
## Full_Rag_Pipeline/
This directory contains a complete pipeline for document ingestion, processing, and retrieval-augmented generation, including a Streamlit app for interactive use.

- **main.py**: Main entry point for the pipeline.
- **pyproject.toml**: Project configuration and dependencies for the pipeline.
- **requirements.txt**: Python dependencies for the pipeline.
- **streamlit_app.py**: Streamlit web application for interacting with the RAG pipeline.
- **uv.lock**: Lock file for dependencies.
- **.env**: Environment variables (should contain API keys and credentials; excluded from version control).
- **data/**: Contains sample data files (e.g., attention.pdf, url.txt).
- **src/**: Source code for the pipeline, organized as follows:
    - **config/**: Configuration files and settings.
    - **document_ingestion/**: Document ingestion logic, including:
        - **document_processor.py**: Main document processing logic.
    - **graph_builder/**: Graph construction logic, including:
        - **graph_builder.py**: Main graph builder implementation.
    - **node/**: Node definitions and logic, including:
        - **nodes.py**: Node implementations.
        - **reactnode.py**: React node logic.
    - **state/**: State management, including:
        - **rag_state.py**: RAG state definitions.
    - **vectorstore/**: Vector store logic, including:
        - **vectorstore.py**: Vector database integration.

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
 **1-chromadb.ipynb**: Introduction and usage of ChromaDB.
 **2-faiss.ipynb**: FAISS vector database usage.
 **3-Othervectorstores.ipynb**: Other vector store implementations.
 **doc_0.txt, doc_1.txt, doc_2.txt**: Sample documents for vector database experiments.
 **embedding.ipynb**: Embedding generation for vector databases.
 **openaiembeddings.ipynb**: Using OpenAI embeddings.
 **PineconeVectorDB.ipynb**: Pinecone vector database usage.

## Langgraph/
 - **1-simplegraph.ipynb**: Introduction to LangGraph with a simple graph example.
 - **2-chatbot.ipynb**: Building a chatbot using LangGraph.
 - **3-DataclassStateSchema.ipynb**: Using dataclass state schemas in LangGraph.
 - **4-pydantic.ipynb**: Integrating Pydantic with LangGraph for data validation.
 - **5-ChainsLangGraph.ipynb**: Implementing chains in LangGraph.
 - **6-chatbotswithmultipletools.ipynb**: Creating chatbots with multiple tools in LangGraph.
 - **requirements.txt**: Dependencies for LangGraph projects.

---

For detailed descriptions, refer to the individual notebook files and scripts. Each notebook or script contains code and explanations for its specific topic.


