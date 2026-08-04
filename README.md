# Layerwise Phase Transition Detection of Evidence-Conditioned Reasoning Collapse in Retrieval-Augmented Clinical Language Models

## Overview

We propose the Evidence Adherence Analysis Framework (EAAF), a framework consisting of existing mechanistic interpretability methods and retrieval-conditioned KL divergence to analyze retrieval influence at each layer of the network in two RAG models with distinct architectures: BioMistral and BioMedLM. This enables examination into how, where, and to what extent retrieved context shapes internal model behavior, independent of what appears at the output level.

---

# Research Question

How does retrieved evidence (in RAG) influence the internal, layer-by-layer representations of clinical language models, and is the evidence integration process consistent across different model architectures?

---

# Setup Instructions

## Install Dependencies

pip install -r requirements.txt

## W&B

Create account at: https://wandb.ai/site/

pip install wandb

wandb login

Use & create API Key to login: https://wandb.ai/authorize?ref=models

---

# Implementation Instructions

## Trial 1

## Trial 2

## Trial 3

## Trial 4

## Trial 5

---

# Datasets

## PubMedQA
https://pubmedqa.github.io/

## MedQA
https://github.com/jind11/MedQA

---

# Project Structure

```text
jsjv-research/
│
├── README.md
├── requirements.txt
├── configs/
│   └── default.yaml
│
├── data/
│   ├── raw/
│   └── processed/
│
├── src/
│   ├── rag_pipeline/
│   ├── tracking/
│   ├── trials/
│   ├── analysis/
│   └── visualization/
│
├── outputs/
│   ├── tensors/
│   ├── logs/
│   ├── tables/
│   └── figures/
│
└── notebooks/
