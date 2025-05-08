# RAG-Explorer: Advanced Retrieval Augmented Generation Projects

Welcome to RAG-Explorer, a comprehensive repository showcasing various implementations of Retrieval Augmented Generation (RAG) systems, from basic to advanced.

## Repository Overview

This repository serves as a learning resource and reference implementation for different RAG architectures, techniques, and use cases. I'll be continuously adding new RAG projects as I explore this fascinating intersection of information retrieval and generative AI.

## Current Projects

### 1. Basic RAG Implementation (Current)

A foundational RAG system using Ollama with local language models:

- **Features:**
  - Vector database with semantic search capabilities
  - Embeddings using CompendiumLabs' embedding model
  - Cosine similarity for retrieval
  - Generation using Llama 3.2 (1B Instruct)
  - Simple but effective demonstration of RAG concepts

- **Technology stack:**
  - Python
  - Ollama for local model inference
  - CompendiumLabs embeddings
  - Llama 3.2 for text generation

- **Sample dataset:** Collection of cat facts to demonstrate knowledge retrieval

## Upcoming Projects

I'm planning to expand this repository with the following RAG implementations:

1. **Hybrid RAG Pipeline**
   - Combining keyword search and semantic search
   - Implementing re-ranking techniques
   - Adding metadata filtering

2. **RAG with Document Chunking Strategies**
   - Various text chunking approaches
   - Overlapping chunks for better context preservation
   - Evaluating different chunking strategies

3. **Multi-Vector RAG**
   - Storing multiple embeddings per document
   - Parent-child relationships between chunks
   - Hierarchical retrieval systems

4. **RAG with Advanced Context Management**
   - Dynamic context window handling
   - Context compression techniques
   - Managing retrieval for long documents

5. **Self-Query RAG**
   - Query decomposition
   - Query transformation
   - Multi-step retrieval processes

6. **Fine-tuned RAG System**
   - Custom embedding models
   - Domain-specific knowledge bases
   - Optimizing for specific use cases

## Getting Started

Each project folder contains:
- Complete source code
- README with explanations and usage instructions
- Requirements file for dependencies
- Sample data (when applicable)

To run the basic RAG implementation:

1. Ensure you have Ollama installed
2. Clone this repository
3. Navigate to the basic-rag folder
4. Run `python basic-rag.py`

## Contribution

Feel free to contribute to this repository by:
- Suggesting improvements to existing implementations
- Recommending new RAG techniques to explore
- Sharing your own RAG projects or use cases

## Resources

Interested in learning more about RAG? Check out these resources:
- [LangChain RAG documentation](https://python.langchain.com/docs/modules/data_connection/)
- [LlamaIndex RAG guide](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html)
- [Haystack RAG pipelines](https://haystack.deepset.ai/tutorials/25_rag)
- ["Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks" paper](https://arxiv.org/abs/2005.11401)

## License

MIT license
