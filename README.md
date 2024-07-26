# Lightweight Fine-Tuning with Hugging Face PEFT

## Project Introduction

Lightweight fine-tuning is an essential technique for adapting foundation models, enabling modifications without substantial computational resources. This project applies parameter-efficient fine-tuning using the Hugging Face PEFT (Parameter-Efficient Fine-Tuning) library.

## Project Summary

This project demonstrates:

1. Loading and evaluating a pre-trained model.
2. Performing parameter-efficient fine-tuning using the pre-trained model.
3. Performing inference using the fine-tuned model and comparing its performance to the original model.

## Key Concepts

Hugging Face PEFT allows fine-tuning of a model without altering all its parameters. The process involves:

1. Creating a PEFT config.
2. Converting the model into a PEFT model using this config.

### Prerequisites

- Python 3.x
- PyTorch
- Hugging Face Transformers
- Hugging Face PEFT

### Installation

Install the required libraries:

```bash
pip install torch transformers peft
```

### Running the Notebook

Load and run the provided Jupyter notebook `Lightweight_tuning_complete.ipynb` to reproduce the results.

## License

This project is licensed under the MIT License.

