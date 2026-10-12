# Hi, I'm Long

CS student at UC San Diego. I've interned at Workday, IBM, and an early-stage startup, and I'm currently a Software Developer Intern at IBM.

Most of my work has been in AI engineering:

- **AI agents.** Agents that triage issues and work across internal tools, with evals to catch wrong answers.
- **RAG.** Retrieval over docs, code, and tickets with vector search and guardrails.
- **MCP.** Connecting agents to internal tools and data through the Model Context Protocol.

Outside of AI, I got curious about low-level programming and general software engineering. So I picked up Go and C++ and started building systems projects to learn how these systems work.

## Highlighted projects

- **Vector search engine (C++).** HNSW index built from scratch. Searches 1M vectors in 45 µs at 95% recall, with 1.3 to 1.7x the throughput of FAISS. Uses lock-free reads to scale across 10 cores.
- **Log ingestion pipeline (Go).** Go microservices that stream logs through gRPC and Kafka at 69.7K logs/sec. Zero logs lost across 17 chaos tests, with Redis caching and rate limiting on the search API.
- **AI resume search (Python).** Led a 5-person team building a resume search engine for recruiters. Fine-tuned a reranking model that raised top-5 accuracy from 40% to 80%.

## Contact

[LinkedIn](https://linkedin.com/in/long-hodac) · lhodac@ucsd.edu
