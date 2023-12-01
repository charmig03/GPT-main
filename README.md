# Overview
This repository contains code for training and generating text using a GPT language model. A training method using the OpenWebText dataset is shown for the model, which is built in Python.

# Files
1. **train.py:** Training script for the GPT model. It loads the OpenWebText dataset, preprocesses it, and trains the model.
2. **generate.py:** Script for generating text using a pre-trained GPT model. It loads a trained model and generates text based on a given context.
3. **model.py:** Defines the GPT model architecture, including components like MultiHeadAttention, TransformerBlock, TokenEmbedding, and the main GPT model.
4. **utils.py:** Contains utility functions, including text generation using the trained model and a Loader class for downloading pre-trained weights.
5. **config.py:** Configuration file with hyperparameters for training and model architecture.
6. **demo.ipynb:** A Jupyter Notebook demonstrating the usage of the GPT model for training and text generation.

# How to Use
**Training**
- Run train.py to start training the GPT model on the OpenWebText dataset.

**Text Generation**
- Use generate.py to generate text using a pre-trained model.
- Specify the model directory, context, and other parameters as command-line arguments.

  # Dependencies
- TensorFlow
- TensorFlow Text
- Keras NLP
- TensorFlow Datasets

  
