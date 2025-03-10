# Patent Text Analysis Project

This project provides tools for extracting, analyzing, and processing text from patent documents using Python. It leverages OpenAI's embeddings API for semantic analysis and includes utilities for PDF text extraction and token management.

## Features

- PDF text extraction and paragraph segmentation
- Text embeddings generation using OpenAI's API
- Token counting and management using tiktoken
- DataFrame-based text analysis
- Support for both standard OpenAI API and Vocareum environments

## Prerequisites

- Python 3.7+
- Required Python packages:
```bash
  pip install pandas openai PyPDF2 tiktoken
```


export OPENAI_API_KEY="your-api-key"
# Optional for Vocareum users
export OPENAI_API_BASE="https://openai.vocareum.com/v1"


## License
MIT License