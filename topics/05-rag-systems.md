# 05 — RAG Systems (Retrieval-Augmented Generation)

> Status: 🔲 Not started | Stage 4 of roadmap

## What to Learn

### Core Concepts
- Why RAG? (hallucination, knowledge cutoff, private data)
- Indexing pipeline: load → chunk → embed → store
- Retrieval pipeline: query → embed → search → rank
- Generation: context + query → LLM → answer

### Components
- **Document Loaders** — PDF, web, CSV, Notion
- **Text Splitters** — recursive, semantic, token-based
- **Embedding Models** — OpenAI, HuggingFace `all-MiniLM-L6-v2`
- **Vector Stores** — FAISS (local), ChromaDB, Pinecone (cloud)
- **Retrievers** — similarity search, MMR, hybrid

### Evaluation
- Faithfulness (is the answer grounded in context?)
- Answer relevancy (does it answer the question?)
- Context recall (did retrieval find the right chunks?)

## Resources

- [ ] [LangChain RAG tutorial](https://python.langchain.com/docs/tutorials/rag/)
- [ ] [RAGAS evaluation framework](https://github.com/explodinggradients/ragas)

## Notes

*Add notes here as you learn*

## Practice Projects

- [ ] RAG over a PDF (build on AI_Enterprise_Systems work)
- [ ] Compare chunking strategies on same document
- [ ] Evaluate with RAGAS
