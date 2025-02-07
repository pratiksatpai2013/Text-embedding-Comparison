📌 Comparing Free Text Embedding Models: Hugging Face vs. OpenAI

📖 Overview

This project compares the performance of free text embedding models available on Hugging Face and OpenAI to evaluate their effectiveness in generating meaningful vector representations of text.

🏆 Objective

The goal of this study is to assess:

Embedding quality: How well the embeddings capture semantic similarity.

Model efficiency: Time taken to generate embeddings.

Practical usability: Ease of integration and API limitations.

📊 Models Compared

Hugging Face Models

sentence-transformers/all-MiniLM-L6-v2

sentence-transformers/paraphrase-MiniLM-L6-v2

intfloat/multilingual-e5-large

OpenAI Model

text-embedding-ada-002

⚙️ Methodology

Used a benchmark dataset of diverse text samples.

Generated embeddings using each model.

Compared cosine similarity scores for semantically similar and dissimilar text pairs.

Evaluated inference time and API constraints.
