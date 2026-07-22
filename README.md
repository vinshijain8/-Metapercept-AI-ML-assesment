# AI Assessment

## Overview

This repository contains the solutions for the AI Assessment completed using Google Colab.

The notebook includes two assessments demonstrating Retrieval-Augmented Generation (RAG), semantic search, vector databases, and knowledge graphs.

## Assessment 1: Mini RAG Pipeline with ChromaDB

### Objective

Build a simple Retrieval-Augmented Generation (RAG) pipeline.

### Features

* Uses 5 hardcoded documents.
* Preprocesses text by converting it to lowercase and removing punctuation.
* Generates sentence embeddings using the `all-MiniLM-L6-v2` Sentence Transformer model.
* Stores embeddings in ChromaDB.
* Retrieves the most relevant document based on cosine similarity.
* Returns the retrieved document as the response.

## Assessment 2: Knowledge Graph with Semantic Search

### Objective

Build a basic RDF knowledge graph and perform semantic search over its triples.

### Features

* Creates an RDF knowledge graph using `rdflib`.
* Converts RDF triples into natural language sentences.
* Generates embeddings using the `all-MiniLM-L6-v2` Sentence Transformer model.
* Stores embeddings in ChromaDB.
* Accepts a user query and retrieves the most relevant knowledge statement using semantic similarity.

## Technologies Used

* Python
* Google Colab
* Sentence Transformers
* ChromaDB
* RDFLib

## Installation

Install the required libraries:

```bash
pip install chromadb sentence-transformers rdflib
```

## How to Run

1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Run all notebook cells from top to bottom.
4. Enter a query when prompted to retrieve the most relevant result.

## Project Structure

```
AI_Assessment.ipynb
README.md
```

## Author

**Vinshi Jain**
