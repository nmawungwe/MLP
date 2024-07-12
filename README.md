# Multi-Layer Language Model

This repository contains the implementation of a multi-layer language model based on the Bengio et al. (2003) paper. The model is trained to predict the next character in a sequence given a context of previous characters.

## Description

This project implements a character-level language model using PyTorch. The model is trained on a dataset of names and learns to predict the next character in a sequence. The model architecture consists of an embedding layer, a fully connected hidden layer with a tanh activation, and an output layer that produces logits for each character in the vocabulary.

## Requirements

- Python 3.6+
- PyTorch 1.7+
- matplotlib

To install the necessary packages, run:

```bash
pip install -r requirements.txt