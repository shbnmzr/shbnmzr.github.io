---
layout: default
---
## Overview

Below is a selection of projects spanning graph learning, NLP, reinforcement learning, and classical computer science. Each project reflects hands-on implementation of concepts from my coursework and research.

---

## Graph-meta — Metagenomic Classification via GNNs

**Type:** Master's Thesis Research Project  
**Date:** March 2025 – April 2026  
[GitHub →](https://github.com/shbnmzr)

A novel hybrid architecture combining deep learning and graph neural networks for taxonomic classification of metagenomic sequences. The system models structural relationships between assembled genomic contigs as a graph, enabling the model to exploit topological information unavailable to sequence-only methods.

**Technologies:** Python · PyTorch · PyTorch Geometric · NetworkX · HPC

> See [Research](research.md) for a full description.

---

## Learning from Drug Interaction Networks

**Type:** Graduate Course Project (Learning from Networks)  
**Date:** Fall 2024  
[GitHub →](https://github.com/shbnmzr)

A graph-based analysis of drug-drug interaction (DDI) networks, developed in collaboration with a fellow graduate student. The project combined network analysis with machine learning to identify potentially dangerous or unknown drug interactions.

**What was built:**
- Applied centrality measures and clustering algorithms to characterize network topology and identify structurally important drugs.
- Implemented **link prediction** models to surface potential undiscovered interactions, with implications for pharmacovigilance.
- Built interactive visualizations of the DDI network to highlight high-risk interaction clusters.

**Technologies:** Python · NetworkX · Scikit-learn · Matplotlib

---

## LLM-based Knowledge Retrieval System (RAG)

**Type:** Independent Project  
**Date:** Spring 2024  
[GitHub →](https://github.com/shbnmzr)

A scalable **Retrieval-Augmented Generation (RAG)** pipeline designed for contextual question answering over unstructured technical literature. Built to explore the architecture required for grounding language model outputs in domain-specific document corpora.

**What was built:**
- Integrated **FAISS** vector databases for fast embedding-based retrieval of relevant document chunks.
- Constructed a conversational agent using **LangChain**, combining a document retriever with a generative language model pipeline.
- Demonstrated practical AI for question answering: the system returns coherent, context-aware responses grounded in retrieved passages rather than parametric knowledge alone.

**Technologies:** Python · LangChain · FAISS · HuggingFace Hub · OpenAI API

---

## Aftab — Benchmarking CNN Feature Extractors in DRL

**Type:** Research Project (In Preparation for Publication)  
**Collaborators:** Shieenavaz, Zareshahraki, Nanni  
**Supervisor:** Dr. Loris Nanni  
[GitHub →](https://github.com/shbnmzr)

A systematic benchmarking study investigating architectural modifications to the standard Nature DQN convolutional feature extractor. The project evaluates whether alternative CNN architectures improve baseline performance across standard deep reinforcement learning tasks.

> See [Publications](publications.md) for the manuscript status.

**Technologies:** Python · PyTorch · OpenAI Gym

---

## NFA to DFA Converter and DFA Reduction Tool

**Type:** Undergraduate Course Project (Automata Theory)  
**Date:** Spring 2021  
[GitHub →](https://github.com/shbnmzr)

A formal automata toolkit implementing classical algorithms from theoretical computer science.

**What was built:**
- Implemented the **Subset Construction algorithm** to convert Nondeterministic Finite Automata (NFA) to equivalent Deterministic Finite Automata (DFA).
- Integrated **DFA minimization** algorithms to reduce the state space of the resulting automaton.
- Built a validation engine to test whether input strings are accepted by the constructed DFA, with graphical state-transition visualizations.

**Technologies:** Python · Graphviz

---

## Technical Skills Summary

**Languages:** Python · R · Bash  
**ML/DL:** PyTorch · PyTorch Geometric · Scikit-learn · HuggingFace  
**Graph & Networks:** NetworkX · PyG · spectral methods  
**NLP:** LangChain · FAISS · Transformers  
**Infrastructure:** Git · Docker · Linux · HPC (SLURM)
