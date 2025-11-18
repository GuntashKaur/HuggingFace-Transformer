🚀This repository contains a beginner-friendly Jupyter Notebook that demonstrates the essential workflows of HuggingFace Transformers, focusing on how to use pre-trained models for common NLP tasks, compare different tokenizers, and perform inference using PyTorch.

✔️ Using HuggingFace Pipeline
   -

A simple, high-level interface to run pre-trained models for:
A) Sentiment Analysis
B) Named Entity Recognition (NER)

The notebook shows how these pipelines work, what they return, and how easily they can be adapted to different tasks.

✔️ Working with Pre-trained Tokenizers
   -
You will explore:
A) How tokenizers break text into tokens
B) How text turns into numerical IDs
C) How decoding works
D) The differences between tokenizers like
  - BERT (bert-base-uncased)
  - XLNet (xlnet-base-cased)

This helps you visually understand tokenization behavior across models.

✔️ HuggingFace + PyTorch Inference
   -

The notebook demonstrates:
A) Preparing inputs with return_tensors="pt"
B)Running a forward pass using a Transformer model
C) Extracting logits
D) Converting logits to predicted class labels using id2label

This section gives a clear idea of how to use pre-trained Transformer models with PyTorch for custom tasks.
