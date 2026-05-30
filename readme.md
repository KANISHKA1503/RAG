
# RAG (Retrieval-Augmented Generation)

A Retrieval-Augmented Generation system that combines document retrieval with language model generation for enhanced contextual responses.

## Overview

This project implements a RAG pipeline that retrieves relevant documents and uses them to augment large language model responses, improving accuracy and relevance.

## Features

- Document retrieval and indexing
- Augmented generation with context
- Easy-to-use Jupyter notebook interface
- Configurable models and parameters

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- pip (Python package manager)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/KANISHKA1503/RAG.git
   cd RAG
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Open and run the Jupyter notebook:
```bash
jupyter notebook Doc_rag.ipynb
```

Follow the cells in the notebook to:
- Load your documents
- Build the retrieval index
- Generate augmented responses

## Project Structure

```
RAG/
├── Doc_rag.ipynb          # Main notebook with RAG implementation
├── readme.md              # Documentation
└── requirements.txt       # Python dependencies
```

## Technologies Used

- Python
- Jupyter Notebook
- LLM frameworks
- Vector databases




