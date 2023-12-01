# Transformers
Building a basic transformer using Pytorch and using the encoder side of transformer to perform a basic task like reverse a sequence.
Basic Transformer Implementation

## Project Overview
This project involves implementing a basic transformer from scratch using PyTorch. The primary objective is to gain a deeper understanding of the transformer architecture's inner workings​​.

### The code file contains:
Implementation of Transformer Components: Implement various components of a transformer model in PyTorch without using high-level transformer-specific libraries. Components include Embeddings and position embeddings, Multi Head Attention, Transformer Encoder Block and Transformer Decoder Block

Training the Transformer: The model is trained to reverse a sequence of up to five integers (ranging from 1 to 9). This involves generating a synthetic dataset, tokenizing data, creating a training loop, and writing a function to generate output from the trained model​​.

Model Architecture Diagram: A detailed diagram of the implemented architecture, including the dimensions of inputs/outputs at each step​​. On a high level our model use encoder only architecture to so the defined task

Model Evaluation: Quantitative evaluation of the model's performance and commentary on the results.

Improvements: Model showed siginificant improvements by manipulating hyperparameters like reducing the sizes of embedding dimension, head size and epochs. And the acccuracy went up to 96%.

### Setup and Requirements
Language: Python

Framework: PyTorch

Environment: Environment setup details can be found in environment.yml.
