# RAG System PRD

## Problem
Users need accurate answers grounded in internal or external knowledge.

---

## Workflow

1. user query
2. retrieve relevant documents
3. generate response
4. show answer + sources

---

## System Design

- ingestion pipeline
- embedding model
- vector DB
- retrieval layer
- LLM generation

---

## Key Decisions

- chunking strategy
- retrieval top-k
- reranking
- prompt structure

---

## Evaluation

- answer accuracy
- grounding quality
- hallucination rate
- retrieval relevance

---

## Metrics

- query success rate
- user satisfaction
- latency
- cost per query

---

## Guardrails

- always show sources
- fallback when no data
- avoid fabricated answers

---

## Risks

- poor retrieval
- outdated data
- hallucination
