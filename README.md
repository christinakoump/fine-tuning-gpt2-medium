# fine-tuning-gpt2-medium
fine-tuning a pretrained GPT-2 Medium model on the subset (30%) WikiText-2 dataset for text generation tasks using PyTorch and Hugging Face Transformers.
Implements:

-Tokenization and dataset preparation

-Training with mixed precision (AMP)

-Cosine learning rate scheduler

-Gradient clipping

-Validation + perplexity tracking

-Saves the best-performing model

-Generates text using the fine-tuned model
