# Text-to-Image AI

This project implements a text-to-image generation AI model using **Garido** and **ChromaDB**. The system converts natural language text prompts into high-quality images and uses ChromaDB for efficient vector-based search and retrieval.

## Features

- **Text-to-Image Generation**: Transforms textual descriptions into images.
- **Efficient Image Retrieval**: Leverages ChromaDB to store and retrieve images based on vector similarity.
- **Fast Search and Matching**: Uses vector embeddings to quickly find relevant images based on input prompts.
- **Garido Model**: Custom text-to-image model trained on vast datasets to create realistic images from descriptions.

## Technology Stack

- **Garido**: Core model for text-to-image generation.
- **ChromaDB**: Vector search database used for storing and retrieving image embeddings.
- **Python**: Backend language for API development.
- **Flask/FastAPI**: (Optional) Web framework for serving the API.
- **Docker**: Containerization for deployment.

## Prerequisites

- Python 3.8+
- Install dependencies:
```bash
git clone https://github.com/HarshKochar9008/Text-Search
```
  ```bash
  pip install -r requirements.txt
