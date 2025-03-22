# Fine-Tuning Models Using PEFT

## Overview

This repository provides Jupyter notebooks demonstrating the fine-tuning of various language models using Parameter-Efficient Fine-Tuning (PEFT) techniques. The models fine-tuned include:

- **Llama 3.2B**: A 3.2 billion parameter model from the Llama series.&#8203;:contentReference[oaicite:0]{index=0}
- **Llama 3 8B**: :contentReference[oaicite:1]{index=1}&#8203;:contentReference[oaicite:2]{index=2}
- **Bloom-560m**: :contentReference[oaicite:3]{index=3}&#8203;:contentReference[oaicite:4]{index=4}
- **DeepSeek-R1-Distill-Llama-8B**: :contentReference[oaicite:5]{index=5}&#8203;:contentReference[oaicite:6]{index=6}

## Notebooks

Each notebook focuses on fine-tuning a specific model:

- `Fine_tuning_Llama3.2_3B.ipynb`: :contentReference[oaicite:7]{index=7}&#8203;:contentReference[oaicite:8]{index=8}
- `Fine_tuning_Llama3_8B.ipynb`: :contentReference[oaicite:9]{index=9}&#8203;:contentReference[oaicite:10]{index=10}
- `Fine_tuning_bloom-560m.ipynb`: :contentReference[oaicite:11]{index=11}&#8203;:contentReference[oaicite:12]{index=12}
- `Fine-tuning-DeepSeek-R1-Distill-Llama-8B.ipynb`: :contentReference[oaicite:13]{index=13}&#8203;:contentReference[oaicite:14]{index=14}

## Prerequisites

To run these notebooks, ensure you have the following installed:

- :contentReference[oaicite:15]{index=15}&#8203;:contentReference[oaicite:16]{index=16}
- :contentReference[oaicite:17]{index=17}&#8203;:contentReference[oaicite:18]{index=18}
- :contentReference[oaicite:19]{index=19}&#8203;:contentReference[oaicite:20]{index=20}
- :contentReference[oaicite:21]{index=21}&#8203;:contentReference[oaicite:22]{index=22}
- :contentReference[oaicite:23]{index=23}&#8203;:contentReference[oaicite:24]{index=24}

Install the necessary packages using:

```bash
pip install torch transformers peft jupyter
