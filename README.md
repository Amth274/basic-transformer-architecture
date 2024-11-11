# Transformer Model from Scratch

This repository provides a transformer model built from scratch using PyTorch, implementing a simplified version of the Transformer architecture used in NLP tasks. This model can be adapted for tasks such as language translation, sequence-to-sequence modeling, and text generation.

## Features

- Multi-head self-attention mechanism
- Positional encoding for sequence order information
- Encoder and decoder blocks as specified in the original Transformer architecture
- Configurable hyperparameters including embedding size, number of heads, layers, dropout, and maximum sequence length

## Model Architecture

The model includes the following key classes:
- **SelfAttention**: Implements scaled dot-product attention with multiple heads.
- **TransformerBlock**: Combines self-attention with a position-wise feed-forward network.
- **Encoder**: Processes the input sequence and creates context-rich embeddings.
- **Decoder**: Generates the output sequence by attending to both the input sequence and previously generated outputs.
- **Transformer**: Integrates the encoder and decoder with padding and sequence masks for training.

## Requirements

To run the model, you need:
- Python 3.6 or later
- PyTorch 1.7.0 or later

Install dependencies:
```bash
pip install torch
