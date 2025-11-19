# ADS - Agentic Design Synthesis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Hugging Face Datasets](https://img.shields.io/badge/🤗-HuggingFace%20Datasets-blue)](https://huggingface.co/NOKHAB-Lab)
[![DOI](https://zenodo.org/badge/1049752514.svg)](https://doi.org/10.5281/zenodo.17465078)

This repository hosts **comprehensive datasets** for fine-tuning Large Language Models (LLMs) on VHDL hardware design tasks, covering the complete RTL development flow from design generation to FPGA implementation.

---


## 📊 Dataset

###  [LLM_4_VHDL](https://huggingface.co/datasets/NOKHAB-Lab/LLM_4_VHDL) - VHDL Design Generation

---

## 🚀 Getting Started

### Quick Start with Datasets

```python
from datasets import load_dataset

# Load VHDL generation dataset
vhdl_dataset = load_dataset("NOKHAB-Lab/LLM_4_VHDL")
```

### Example Usage

#### VHDL Generation
```python
prompt = "Design a 4-bit counter with synchronous reset and enable signal"
# Model generates VHDL implementation
```

## 📜 License

This project and all associated datasets are released under the **MIT License**.  
You are free to use, modify, and redistribute this work with proper attribution.
