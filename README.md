# 📊 Project Title: *Transformers And Attention Mechanisms*

## 📝 Overview

This repository is structured as a multi-week exploration of sequence modeling and attention-based architectures:

- **🗓️ Week 1:** Manual implementation of attention mechanisms and neural machine translation (NMT).
- **🗓️ Week 2:** Building Transformer models from scratch using Keras.
- **🗓️ Week 3:** Fine-tuning state-of-the-art BERT and GPT models with HuggingFace on the Yelp Review Full dataset.

Each week includes relevant code, experiments, and documentation to guide you through the concepts and practical steps.

---

## 📁 Project Structure


```
Transformers/
│
├── requirements.txt        # List of Python packages needed to run the project
├── README.md               # Project description and usage guide (this file)
├── .gitignore              # Ignore virtual environments, model files, etc. in Git
├── venv/                   # Python virtual environment (should be ignored by git)
│
├── week_1/                 # Week 1: Neural Machine Translation (NMT) with Attention
│   ├── nmt_with_attention.ipynb   # Jupyter notebook for building and training an attention-based NMT model
│   ├── artifacts/                 # Saved model outputs and experiment results
│   │   ├── dynamic_translator/    # Outputs from dynamic translator experiments
│   │   └── translator/           # Outputs from standard translator experiments
│   └── README.md                 # Week 1 overview and instructions
│
├── week_2/                 # Week 2: Transformer-based NMT with Keras
│   ├── transformer.ipynb         # Jupyter notebook for building and training a Transformer model using Keras
│   ├── model.png                 # Architecture diagram of the Transformer model
│   ├── artifacts/                # Saved model outputs and experiment results
│   └── README.md                 # Week 2 overview and instructions
│
├── week_3/                 # Week 3: Fine-tuning BERT and GPT on Yelp Reviews
│   └── fine_tune_hug.ipynb       # Notebook for fine-tuning and evaluating BERT/GPT models on Yelp Review Full dataset
│   │                             # Includes data loading, tokenization, training, evaluation, and comparison of architectures
│   └── README.md                 # Week 3 overview and instructions
```

---

## 🔧 Setup and Installation Instructions

### 🚀 OPTION 1: Use Google Colab

For a quick start, open the notebooks directly in [Google Colab](https://colab.research.google.com/) or upload the notebook files from this repository to your Colab workspace.

### 💻 OPTION 2: Run Locally

#### 1️⃣ Create a virtual environment and activate it

It's recommended to create a different environment for each week to avoid conflicts.

#### 🖥️ macOS & Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

#### 🪟 Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### 📦 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🛠️ Step-by-Step Guide

Check every week content.

### Step [1]:
Go to [Week 1](week_1/README.md) folder and check the readme to proceed forward.


### Step [2]:
Go to [Week 2](week_2/README.md) folder and check the readme to proceed forward.

### Step [3]:
Go to [Week 3](week_3/README.md) folder and check the readme to proceed forward.

---

## 🏆 Results

We successfully implemented the Transformer architecture and explored attention mechanisms in depth. By the final week, we fine-tuned cutting-edge GPT 🤖 and BERT 🧠 models using HuggingFace on the Yelp Review Full dataset. The journey was both challenging and rewarding, offering hands-on experience with state-of-the-art NLP techniques and delivering impressive results on real-world data 📈.
