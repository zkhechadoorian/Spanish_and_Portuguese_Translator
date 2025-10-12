# 📊 Project Title: *Neural machine translation with attention*

## 🌍 Overview

This project tackles the challenge of translating text between languages using **neural machine translation (NMT)** models enhanced with **attention mechanisms**. 

### ❓ Why Traditional Systems Fall Short
- Struggle to capture long-range dependencies
- Often produce inaccurate or unnatural translations

### 🚀 Our Solution: Attention-Based NMT
- Improves translation quality and fluency
- Better contextual understanding

### 💡 Applications
- Cross-lingual communication
- Content localization
- Automated translation services

By leveraging attention, this project delivers more accurate and context-aware translations, making it highly valuable for real-world multilingual scenarios.

---

## 📁 Project Structure


```
1_nmt_translation/
│
├── artifacts/                            # Saved generated artifacts such as exported trained models.
|-- assets /                              # Saved generated images.
│   ├── dynamic_translator/               # Saved dynamic translator outputs (see notebook for details).
│   ├── translator/                       # Saved translator outputs (see notebook for details).
│
├── nmt_with_attention.ipynb              # Entery point which is Notebook for model explanation and training.
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
```bash
pip install 'tensorflow==2.15.0' 'tensorflow-text>=2.11' 'matplotlib>=3.7.0' 'einops==0.6.0'
```

---

## 🛠️ Step-by-Step Guide


### Step [1]:

Open file [nmt_with_attention.ipynb](nmt_with_attention.ipynb) then follow up every cell execution until the end.

---

## 📊 Results

After running all cells in `nmt_with_attention.ipynb`, you will find the final evaluation metrics, tables, and sample translations in the notebook's last section. 

- **Training Metrics Table:** Displays loss values (using categorical cross-entropy) and accuracy scores recorded during training, providing insight into model learning progress and performance.
- **Sample Translations:** Example input sentences and their translated outputs, demonstrating model effectiveness.


### 📈 Suggested Improvements

- **Expand Evaluation:** Include additional metrics such as BLEU, ROUGE in addidtion to METEOR scores for a more comprehensive assessment of translation quality.


