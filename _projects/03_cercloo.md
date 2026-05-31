---
layout: page
title: Cercloo
description: 6-stage agentic HR data migration pipeline with GraphRAG and UAE/KSA compliance
img: assets/img/projects/cercloo.png
importance: 3
category: agents
github: muhnehh/cercloo
---

Inspired by [Cercli (YC S23)](https://cercli.com), Cercloo is an open-source agentic pipeline
for migrating messy HR CSVs into compliance-ready HRIS artifacts.

**Pipeline stages:** discover -> profile -> embed -> map -> comply -> export

- **GraphRAG** models cross-entity HR relationships (employee, contract, payroll, leave)
- UAE/KSA labor-law compliance checks built in
- Human-in-the-loop review for low-confidence field mappings

**Stack:** Python · GraphRAG · FAISS · LangChain