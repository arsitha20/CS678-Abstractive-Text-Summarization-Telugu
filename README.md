# Telugu Text Summarization
Implemented Telugu text summarization using the multilingual T5 (mT5) model.

## Overview
This project uses the mT5 model fine-tuned on Telugu stories to generate concise summaries while preserving the meaning of the original text. The implementation is available as a notebook that can be run directly in Google Colab.

## Features
- Abstractive text summarization for Telugu language using mT5.
- Interactive story input through notebook interface.
- ROUGE score evaluation metrics.
- Experiment tracking using Weights & Biases.

## Requirements
- Python 3.6+
- PyTorch
- Transformers
- Rouge-score
- Wandb (for experiment tracking)
- Pandas
- NumPy

## Run
Google Colab (Recommended)
- Open the notebook in Google Colab.
- Ensure you're using a GPU runtime.
- Run all cells in sequence.
- When prompted, enter Telugu story.
- The model will generate a summary for the story provided as prompt.
