---
layout: page
title: RAGEval
description: CLI evaluation harness for RAG pipelines with automated QLoRA fine-tuning
img: assets/img/projects/rageval.png
importance: 2
category: LLMs
github: muhnehh/rag-eval
---

A CLI harness integrating RAGAS metrics with an automated fine-tuning flywheel.

**RAGAS scores on synthetic financial QA:**

| Metric | Score |
|---|---|
| Faithfulness | 0.88 |
| Context Recall | 0.91 |
| Answer Relevancy | 0.97 |

- QLoRA fine-tuning on Phi-3-mini
- Git-tagged metric versioning across evaluation runs
- Supports custom dataset preparation pipelines

**Stack:** Python · RAGAS · QLoRA · LangChain · FAISS