# Layerwise Phase Transition Detection of Evidence-Conditioned Reasoning Collapse in Retrieval-Augmented Clinical Language Models

## Overview

This project studies why hallucinations still happen in Retrieval-Augmented Generation (RAG) systems, even when relevant evidence is retrieved.

---

# Research Question

Can hallucinations in clinical RAG systems be detected internally before they appear in final outputs?

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