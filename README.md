# Light-Weight Fine-Tuning

This repository demonstrates how to apply parameter-efficient fine-tuning techniques to adapt large language models (LLMs) for specific tasks without substantial computational resources.

## Overview

Fine-tuning large pre-trained models can be resource-intensive. Parameter-Efficient Fine-Tuning (PEFT) methods, such as Low-Rank Adaptation (LoRA), enable the adaptation of these models by updating only a small subset of parameters, reducing computational overhead while maintaining performance.

## Project Structure

- **`LightweightFineTuning.ipynb`**: Jupyter Notebook containing the implementation of the fine-tuning process.
- **`fine_tuned_peft_model/`**: Directory containing the saved weights of the fine-tuned model.
- **`results/`**: Directory containing evaluation results and metrics.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- PyTorch
- Hugging Face Transformers
- Hugging Face PEFT Library
- Jupyter Notebook

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/dustinober1/Light-Weight-Fine-Tuning.git
   cd Light-Weight-Fine-Tuning```
