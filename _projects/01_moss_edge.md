---
layout: page
title: Moss Edge Docs Agent
description: On-device retrieval with ONNX INT8 cross-encoder reranker - 5.58ms median latency
img: assets/img/projects/moss_edge.png
importance: 1
category: edge AI
github: muhnehh/moss-edge-docs-agent
---

Built on the [Moss SDK](https://moss.ai) (YC F25), this agent performs on-device document retrieval
without cloud calls on high-confidence queries.

**Key results:**
- Fine-tuned a cross-encoder reranker and exported to ONNX INT8
- **5.58ms** median retrieval latency · **21.47ms** end-to-end
- Avoids cloud round-trips on high-confidence passages - fully offline capable

**Stack:** Python · ONNX Runtime · PyTorch · Moss SDK