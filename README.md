# Incremental Context Strategies in RAG-Based Chatbots

This repository contains the code, dataset, and experimental results for the paper:

**"Incremental Context Strategies in RAG-Based Chatbots for Hospital Document Retrieval: Evaluating the Trade-off Between Quality and Cost"**

---

## 📌 Overview

This work investigates the impact of context construction strategies in Retrieval-Augmented Generation (RAG)-based chatbots. Specifically, we compare:

- **Fixed context** (Top-50 chunks)
- **Incremental context** (progressive retrieval in Top-5 steps)

The goal is to analyze how context size affects:

- Response quality
- Token consumption (cost)
- Context dilution

---

## 🧠 Key Contributions

- Proposal of an **incremental context construction strategy** for RAG-based chatbots  
- Evaluation of multiple LLMs in a unified experimental setup  
- Demonstration of **token reduction up to 88%**  
- Analysis of **context dilution effects**  
- Multi-dimensional evaluation using:
  - BERTScore
  - LLM-as-a-Judge
  - Token usage  

---

