
# 📊 Project Title: *Fine-tuning BERT and GPT for Sentiment Classification on Yelp Reviews*


## 🌍 Overview

This project demonstrates fine-tuning and evaluating both BERT-based and GPT-based sequence classification models on the Yelp Review Full dataset using Hugging Face Transformers and Datasets libraries.

Key steps include:
- 📦 Loading and preprocessing the Yelp Review Full dataset, including tokenization.
- ✂️ Selecting subsets for training and evaluation.
- 🤖 Initializing BERT and GPT models for sequence classification.
- ⚙️ Setting up training arguments and metrics (accuracy).
- 🏋️‍♂️ Training the models using the Trainer API.
- 🔍 Making predictions on evaluation samples and decoding results.
- ✨ Comparing the performance of BERT and GPT architectures on sentiment classification.

The notebook leverages GPU acceleration for efficient computation and provides insights into the strengths of both BERT and GPT for NLP tasks.

### ❓ Why Traditional Systems Fall Short
- Struggle to capture long-range dependencies
- Often produce inaccurate or unnatural translations

### 🚀 Our Solution: Attention-Based NMT
- Improves translation quality and fluency
- Better contextual understanding


### 💡 Applications
- Sentiment analysis for customer reviews
- Automated content moderation
- Business intelligence from user feedback
- Benchmarking transformer architectures for NLP tasks

By leveraging state-of-the-art transformer models, this project delivers robust and scalable sentiment classification, making it highly valuable for real-world business and research scenarios.

---

## 📁 Project Structure



```
week_3/
│
├── fine_tune_hug.ipynb         # Notebook for fine-tuning and evaluating BERT/GPT models on Yelp Review Full dataset
├── artifacts/*                 # Saved generated artifacts such as exported trained models.
```

---

## 🔧 Setup and Installation Instructions

### 🚀 OPTION 1: Use Google Colab

For a quick start, open the notebooks directly in [Google Colab](https://colab.research.google.com/) or upload the notebook files from this repository to your Colab workspace.

### 💻 OPTION 2: Run Locally

#### 1️⃣ Create a virtual environment and activate it

It's recommended to create a different environment for each week to avoid conflicts.

* Use python 3.11.

#### 🖥️ macOS & Linux

```bash
python3.11 -m venv .venv
source .venv/bin/activate
```

#### 🪟 Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### 📦 2. Install dependencies

```bash
pip install 'transformers[torch]' datasets evaluate scikit-learn accelerate
```

---

## 🛠️ Step-by-Step Guide

### Step 1:
Open [fine_tune_hug](fine_tune_hug.ipynb) and run all cells in `fine_tune_hug.ipynb` to:
- Load and preprocess the Yelp Review Full dataset
- Fine-tune BERT and GPT models for sentiment classification
- Evaluate and compare model performance

---

## 📊 Results

After running all cells in `fine_tune_hug.ipynb`, you will find:

- **Training Metrics Table:** Loss and accuracy scores for BERT and GPT models
- **Evaluation Results:** Model predictions and accuracy on the Yelp Review Full test set
- **Comparison Insights:** Analysis of BERT vs. GPT performance for sentiment classification

### 📈 Model Performance Summary

| Model | Epoch | Training Loss | Validation Loss | Accuracy |
|-------|-------|--------------|----------------|----------|
| BERT  |   0   |   0.9642     |   0.9209       |  0.598   |
| GPT   |   0   |   1.6256     |   1.6187       |  0.200   |

- **BERT** achieves significantly higher accuracy (≈60%) after one epoch, indicating strong performance on sentiment classification.
- **GPT** shows lower accuracy (≈20%) for the same setup, suggesting it may require further tuning or is less suited for this specific classification task.

Review these results to assess the strengths and weaknesses of each transformer architecture for sentiment analysis tasks.
