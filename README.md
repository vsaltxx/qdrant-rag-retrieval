# Homework 6: Vector Databases
[![Python Version](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3110/)
[![Qdrant Version](https://img.shields.io/badge/Qdrant-1.15-red?logo=qdrant&logoColor=white)](https://qdrant.tech/docs/quick-start/)

## Overview
A semestral home assignment focused on the topic of vector databases. In this assignment you will implement a retrieval component for a RAG system-

## Prerequisites
1. Ensure you have [uv installed](https://docs.astral.sh/uv/getting-started/installation/).
2. Make sure that the docker daemon is running.

## Installation
Install the dependencies:
```bash
uv sync
```

## Home Assignment Tasks
1. Task - Data Loading
  - Load data from the Hugging Face dataset and extract appropriate format
2. Task - Collection Creation & Configuration
  - Create a collection with correct vector representations, index configuration, distance functions and so on
3. Task - Data Upload
    - Upload the data into the collection
4. Task - Design Complex Query
  - Employ advanced search techniques such as hybrid search, filtering, reranking and metadata boosting
5. Evaluation
  - Evaluate the retrieval system and achieve at least 80% average precision
