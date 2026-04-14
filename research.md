# Research

[← Home](index.md) · [Projects](projects.md) · [Publications](publications.md)

---

## Research Overview

My research focuses on **graph-based machine learning** and its applications to complex, structured biological data. I am particularly interested in how graph neural networks can model relational structure in domains where traditional sequence-based methods fall short — most concretely, in metagenomic classification and drug interaction analysis.

I approach research with a strong emphasis on rigorous benchmarking, reproducibility, and end-to-end pipeline engineering.

---

## Master's Thesis

### Graph-meta: Improving Metagenomic Classification with Graph-based Learning

**Advisor:** Dr. Matteo Comin, Università degli Studi di Padova  
**Duration:** March 2025 – April 2026  
[View on GitHub →](https://github.com/shbnmzr)

Metagenomics — the study of genetic material recovered directly from environmental samples — presents a challenging classification problem: sequencing reads are short, noisy, and drawn from highly diverse, often unknown microbial communities. Existing taxonomic classifiers rely predominantly on k-mer-based sequence alignment, which struggles with novel organisms and ambiguous contigs.

**Graph-meta** introduces a hybrid deep learning architecture that treats metagenomic assembly graphs as first-class inputs, enabling the model to exploit structural relationships between genomic contigs rather than treating each sequence in isolation.

**Key contributions:**

- Designed a novel hybrid architecture combining **Deep Learning** and **Graph Neural Networks (GNNs)** to classify metagenomic sequences by modeling the structural topology of assembly graphs.
- Built a fully automated bioinformatics pipeline covering reference genome curation from GenBank, read simulation, and *de novo* assembly, producing high-fidelity graph-structured datasets at scale.
- Optimized GNN hyperparameters and message-passing layers for large-scale biological networks, achieving measurable performance gains over state-of-the-art taxonomic classifiers.
- Validated robustness using real-world multi-omic data, demonstrating that graph-based representations resolve ambiguities that sequence-only methods cannot.

**Core technologies:** Python · PyTorch · PyTorch Geometric · NetworkX · HPC (SLURM)

---

## Research Interests & Directions

### Graph Representation Learning
I am interested in the expressive power of GNNs, spectral graph methods, and how structural inductive biases can be leveraged in domains with inherently relational data — from biological networks to knowledge graphs.

### Computational Biology & Bioinformatics
The intersection of machine learning and genomics offers rich, unsolved problems. My thesis work has deepened my interest in applying principled ML methods to sequence data, metagenomics, and multi-omic integration.

### Deep Reinforcement Learning
Through my work on the *Aftab* publication project (supervised by Dr. Loris Nanni), I have investigated architectural modifications to DQN feature extractors and their effect on baseline performance in RL tasks.

### Natural Language Processing
My coursework and independent projects have given me hands-on experience with transformer architectures, retrieval-augmented generation (RAG), and formal grammar theory.

---

## Research Skills

| Area | Methods & Tools |
|---|---|
| Graph Learning | GNNs, spectral clustering, link prediction, centrality, community detection |
| Deep Learning | CNNs, autoencoders, transformers, regularization, explainable AI |
| Bioinformatics | Read simulation, *de novo* assembly, taxonomic classification |
| NLP | RAG, fine-tuning, sequence labeling, dependency parsing |
| Programming | Python (PyTorch, PyG, Scikit-learn, HuggingFace), R, Docker, Linux/Bash, HPC |

---

*Interested in my research? [Get in touch →](contact.md)*
