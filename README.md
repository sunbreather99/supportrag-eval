# SupportRAG-Eval
A grounded, multi-agent RAG system for customer-support knowledge, with built in evaluation of faithfulness and confidence, and drift detection.
**Status: in progress**
## Goals
 -Hybrid retrieval(BM25 + dense embeddings) over support documents
 -Multi-agent pipeline: retriever -> answer -> verifier(abstain when unsupported)
 -Drift detection on query and confidence distributions
 -Dockerized FastAPI service with CI
## Planned stack
Python, PyTorch , Hugging Face , FastAPI , Docker , Github Actions
