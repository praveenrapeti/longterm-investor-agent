# Model Registry

## Purpose
The Model Registry documents the types of AI models assumed in the system design.
It provides clarity on how intelligence, reasoning, and memory retrieval are
handled within the agentic architecture.

This mini project focuses on **design and decision flow**, not on model training
or deployment.

---

## 1. Language Model (LLM)

### Role
The Language Model is responsible for:
- Understanding user queries
- Reasoning across financial, macro, and qualitative inputs
- Generating explainable investment insights
- Coordinating prompt-based agent interactions

### Usage in the System
- Interprets Perceive, Plan, and Act prompts
- Synthesizes outputs from multiple agents
- Produces structured, human-readable recommendations

---

## 2. Embedding Model

### Role
The Embedding Model converts textual information into vector representations so
that the agent can retrieve relevant past information based on meaning.

### Usage in the System
- Semantic search across user profile and portfolio memory
- Retrieval of similar past decisions and watchlist notes
- Context preservation across multiple interactions

---

## 3. Model Selection Rationale
- LLMs provide reasoning, explanation, and natural language interaction
- Embeddings enable efficient and scalable memory retrieval
- Together, they support consistent and explainable long-term decisions

---

## Design Note
This repository documents model usage at a conceptual level only.
No model training, fine-tuning, or inference code is included as part of this
mini project.

