---
permalink: /markdown/
title: "Curated Resources on Large Language Models (LLMs)"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## 📋 Table of Contents
- [Learning Foundations](#-learning-foundations)
- [Deep Dives](#-deep-dives)
  - [RLHF](#-reinforcement-learning-from-human-feedback-rlhf)
  - [Efficient Inference](#-efficient-inference)
  - [Quantization & Compression](#-quantization--compression)
  - [Mixture of Experts](#-mixture-of-experts-moe)
  - [RAG & Vector Databases](#-rag--vector-databases)
  - [Multimodal Learning](#-multimodal-learning)
- [Comprehensive Courses](#-comprehensive-courses)
- [Research Papers](#-research-papers)
  - [Model Optimization](#-model-optimization--compression)
  - [Alignment & Instruction Tuning](#-alignment--instruction-tuning)
  - [Architecture & Training](#-architecture--training)
  - [RAG & Knowledge Retrieval](#-rag--external-knowledge)
  - [Multimodal & Prompting](#-multimodal--prompt-techniques)
- [Fun Content](#-fun-content)

---

## 📚 Learning Foundations

Essential resources for building foundational knowledge of LLMs:

### 🎓 Core Concepts & Architectures

| Resource | Author | Description |
|----------|--------|-------------|
| [LLM Video Series](https://www.youtube.com/@AndrejKarpathy) | Andrej Karpathy | Comprehensive series covering GPT-1, GPT-2, tokenizers, and LLM internals |
| [Rotary Positional Embeddings](https://www.youtube.com/watch?v=o29P0Kpobz0) | Various | Detailed explanation of RoPE embeddings for transformer positional encoding |
| [Building Large Language Models](https://www.youtube.com/watch?v=9vM4p9NN0Ts) | Yann Dubois (Stanford CS229) | Academic lecture on LLM fundamentals and construction |

---

## 🔍 Deep Dives

Detailed explorations of specific LLM technologies and techniques:

### 🤖 Reinforcement Learning from Human Feedback (RLHF)

| Resource | Author | Focus |
|----------|--------|-------|
| [PPO for LLMs Explained](https://www.youtube.com/watch?v=8jtAzxUwDj0) | Julia Turc | Intuitive explanation of Proximal Policy Optimization for language models |
| [DeepSeek's GRPO](https://www.youtube.com/watch?v=xT4jxQUl0X8) | Julia Turc | Group Relative Policy Optimization for reinforcement learning with LLMs |

### ⚡ Efficient Inference

| Resource | Author | Focus |
|----------|--------|-------|
| [Speculative Decoding](https://www.youtube.com/watch?v=S-8yr_RibJ4) | Efficient NLP | Techniques for faster text generation |
| [KV-Cache](https://www.youtube.com/watch?v=80bIUggRJf4) | Efficient NLP | Understanding key-value caching for optimized inference |

### 🔢 Quantization & Compression

| Resource | Focus | Description |
|----------|-------|-------------|
| [Quantization 101](https://www.youtube.com/watch?v=0VdNflU08yA) | Fundamentals | Great starting point for understanding quantization in LLMs |
| [QLoRA Explained](https://www.youtube.com/watch?v=XpoKB3usmKc) | Fine-tuning | Efficient parameter-efficient fine-tuning technique |

### 🧩 Mixture of Experts (MoE)

| Resource | Author | Focus |
|----------|--------|-------|
| [Nano-MoE](https://cameronrwolfe.substack.com/p/nano-moe) | Cameron Wolfe | Step-by-step construction of nanoMoE components |

### 🔍 RAG & Vector Databases

| Resource | Focus | Description |
|----------|-------|-------------|
| [How Vector Databases Work](https://www.youtube.com/watch?v=035I2WKj5F0) | RAG Systems | Fundamentals of vector databases for retrieval-augmented generation |

### 🖼️ Multimodal Learning

| Resource | Focus | Description |
|----------|-------|-------------|
| [Mixed-modal Language Modeling](https://www.youtube.com/watch?v=JYMXlmSM_Ew) | Early Fusion | Covers Chameleon, Transfusion, and Mixture of Transformers for image-text sequences |

---

## 🧠 Comprehensive Courses

Complete educational resources on LLM-related topics:

| Course | Provider | Focus |
|--------|----------|-------|
| [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/unit0/introduction) | Hugging Face | Beginner-friendly introduction to agent-based architectures using LLMs |

---

## 🔬 Research Papers

### 📈 Recent Developments Overview
[The latest LLM research](https://www.youtube.com/watch?v=_Y3BfN9v3sA) - Overview of how LLMs are getting smarter and faster

### 🔧 Model Optimization & Compression

| Paper | Year | Key Contribution |
|-------|------|------------------|
| [MiniLLM: Knowledge Distillation of Large Language Models](https://arxiv.org/abs/2306.08543) | 2023 | Techniques for distilling knowledge from larger models into smaller ones |
| [GPTQ: Accurate Post-Training Quantization](https://arxiv.org/abs/2210.17323) | 2022 | Efficient quantization approach for GPT models |
| [FlashAttention](https://arxiv.org/abs/2205.14135) | 2022 | IO-aware exact attention algorithm with better memory efficiency |
| [The Era of 1-bit LLMs](https://arxiv.org/abs/2402.17764) | 2024 | Extreme quantization showing LLMs can operate with just 1.58 bits |
| [MEGABLOCKS](https://arxiv.org/abs/2211.15841) | 2022 | Efficient sparse training with Mixture-of-Experts |
| [Adaptive Inference-Time Compute](https://arxiv.org/abs/2410.02725) | 2024 | Dynamic resource allocation during inference |

### 🎯 Alignment & Instruction Tuning

| Paper | Year | Key Contribution |
|-------|------|------------------|
| [Instruction-Following Evaluation](https://arxiv.org/abs/2311.07911) | 2023 | Methodologies for evaluating instruction following capabilities |
| [Direct Preference Optimization](https://arxiv.org/abs/2305.18290) | 2023 | Transforming language models into reward models |
| [SELF-INSTRUCT](https://arxiv.org/abs/2212.10560) | 2022 | Aligning models with self-generated instructions |
| [Scaling Instruction-Finetuned Language Models](https://arxiv.org/abs/2210.11416) | 2022 | Techniques for scaling instruction-tuning |

### 🏗️ Architecture & Training

| Paper | Year | Key Contribution |
|-------|------|------------------|
| [GQA: Generalized Multi-Query Transformer Models](https://arxiv.org/abs/2305.13245) | 2023 | Training technique for multi-query attention |
| [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) | 2022 | Principles for optimizing compute during training |
| [TRANSFORMER-SQUARED: Self-Adaptive LLMs](https://arxiv.org/abs/2501.06252) | 2024 | Architecture innovation for adaptive capabilities |
| [Why Do We Need Weight Decay in Modern Deep Learning?](https://arxiv.org/abs/2310.04415) | 2023 | Analysis of regularization techniques |
| [DeepSeekMoE](https://arxiv.org/abs/2401.06066) | 2024 | Expert specialization in MoE language models |
| [Scalable-Softmax for Attention](https://arxiv.org/abs/2501.19399) | 2024 | Improved attention mechanism |
| [LLaMA: Open Foundation Models](https://arxiv.org/abs/2302.13971) | 2023 | Architecture and training of the first LLaMA models |
| [Llama 2](https://arxiv.org/abs/2307.09288) | 2023 | Open foundation and fine-tuned chat models |
| [The Llama 3 Herd](https://arxiv.org/abs/2407.21783) | 2024 | Latest developments in the Llama model family |
| [Finetuned LMs as Zero-Shot Learners](https://arxiv.org/abs/2109.01652) | 2021 | Zero-shot capabilities through finetuning |

### 📚 RAG & External Knowledge

| Paper | Year | Key Contribution |
|-------|------|------------------|
| [Retrieval-Augmented Generation: A Survey](https://arxiv.org/abs/2312.10997) | 2023 | Comprehensive overview of RAG techniques |
| [Data Contamination Quiz](https://arxiv.org/abs/2311.06233) | 2023 | Tool for detecting and estimating training data contamination |

### 🌐 Multimodal & Prompt Techniques

| Paper | Year | Key Contribution |
|-------|------|------------------|
| [Chameleon: Mixed-Modal Early-Fusion](https://arxiv.org/abs/2405.09818) | 2024 | Model for processing and generating mixed-modal data |
| [P-ADAPTERS](https://arxiv.org/abs/2110.07280) | 2021 | Extracting factual information using diverse prompts |

---

## 💼 Fun Content

| Content | Description |
|---------|-------------|
| [How programmers overprepare for job interviews](https://www.youtube.com/watch?v=5bId3N7QZec) | Humorous take on technical interview preparation |

---

## About This Collection

This resource collection was curated with the help of an AI assistant. All links and descriptions have been reviewed, but please report any issues you find.

<a href="#top">Back to Top</a>