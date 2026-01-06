# CRUX
Region-First Knowledge Graph Reasoing for Medical Question Answering

# CRUX: Region-First Knowledge Graph Reasoning for Medical Question Answering

This repository accompanies the paper:

> **CRUX: Region-First Knowledge Graph Reasoning for Medical Question Answering**  
> *(under review)*

---

## 🔍 Overview

CRUX is a **region-first knowledge graph reasoning framework** for medical question answering.
The key idea is to **construct a query-aligned subgraph before reasoning** and constrain all subsequent multi-hop inference to this localized region.
This design reduces retrieval noise, mitigates semantic drift, and improves factual consistency in both discriminative (MCQ) and generative (SAQ) settings.

CRUX dynamically adapts its reasoning strategy based on evidence availability and incorporates a verification mechanism to suppress hallucinated or unsupported inferences.

---

## 📄 Paper

- The paper is currently under peer review.
- A public preprint will be linked here after the review process.

---

## 💻 Code Availability

The source code is **not yet released**.

We are currently preparing the codebase for public release, including documentation and cleanup for reproducibility.
The full implementation will be made available **after the review process**.

> **Status:** 🚧 Code release in progress.

---

## 📊 Benchmarks & Evaluation

CRUX is evaluated on multiple medical QA benchmarks under both multiple-choice (MCQ) and short-answer (SAQ) settings, as well as hallucination-focused benchmarks under generative and adversarial conditions.

Detailed experimental results are reported in the paper.

---

## 📌 Citation

If you find this work useful, please cite our paper:

```bibtex
@article{crux2025,
  title     = {CRUX: Region-First Knowledge Graph Reasoning for Medical Question Answering},
  author    = {Anonymous},
  journal   = {Under review},
  year      = {2025}
}
