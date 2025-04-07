# Fine-Tuning Models

## Overview

This repository provides Jupyter notebooks demonstrating the fine-tuning of various language models using Parameter-Efficient Fine-Tuning (PEFT) techniques. The models fine-tuned include:

- **Llama 3.2B**: A 3.2 billion parameter model from the Llama series.
- **Llama 3 8B**: A 8 billion parameter model from the Llama series.
- **Bloom-560m**: A 560 million parameter model from the Bloom series.
- **DeepSeek-R1-Distill-Llama-8B**: An 8 billion parameter distilled version of the DeepSeek-R1 model.
- **Phi 2**: A 2.7 billion parameter model from the Microsoft's Phi series.
- **GPT 2**: A 1.5 billion parameter model from the OpenAI's GPT series.


## Notebooks

Each notebook focuses on fine-tuning a specific model:

- `Fine_tuning_Llama3.2_3B.ipynb`: Fine-tuning the Llama 3.2B model.
- `Fine_tuning_Llama3_8B.ipynb`: Fine-tuning the Llama 3 8B model.
- `Fine_tuning_bloom-560m.ipynb`: Fine-tuning the Bloom-560m model.
- `Fine-tuning-DeepSeek-R1-Distill-Llama-8B.ipynb`: Fine-tuning the DeepSeek-R1-Distill-Llama-8B model.​
- `Fine-tuning-Phi-2.ipynb`: Fine-tuning the Phi 2 model.​
- `Fine-tuning-GPT-2.ipynb`: Fine-tuning the GPT 2 model.​


## Prerequisites

To run these notebooks, ensure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- PyTorch
- Transformers library from Hugging Face
- PEFT library

Install the necessary packages using:

```bash
pip install torch transformers peft jupyter
```

## Prerequisites


1. Clone this repository:

```bash
git clone https://github.com/ManishSharma1609/Fine-tuning-models.git
cd Fine-tuning-models
```
2. Launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

or
```bash
jupyter lab
```

3. Open the desired notebook and follow the instructions within to fine-tune the respective model.
