# 📊 Project Title: *Neural machine translation with a Transformer and Keras*
## 🌍 Overview

This project focuses on building a **Transformer-based neural machine translation (NMT)** system using Keras. Transformers revolutionize translation tasks by relying entirely on attention mechanisms, enabling efficient modeling of long-range dependencies without recurrence.

### ❓ Limitations of Previous NMT Approaches
- Recurrent models struggle with long sequences and parallelization
- Limited ability to capture complex context

### 🚀 Our Solution: Transformer Architecture
- Utilizes multi-head self-attention for richer contextual understanding
- Enables faster training and inference through parallel computation

### 💡 Applications
- Real-time multilingual communication
- Scalable content localization
- Automated translation for global platforms

By harnessing the power of Transformers, this project achieves state-of-the-art translation quality, making it suitable for demanding, real-world language tasks.

## 📁 Project Structure


```
week_2/
│
├── artifacts/*                    # Saved generated artifacts such as exported trained models.
│
├── transformer.ipynb              # This is the entery point which is a Notebook for model explanation and training.
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
pip install 'protobuf~=3.20.3' tensorflow_datasets tensorflow tensorflow-text matplotlib
```

---

## 🛠️ Step-by-Step Guide


### Step [1]:

Open file [transformer.ipynb](transformer.ipynb) then follow up every cell execution until the end.

---

## 📊 Results

After running all cells in `transformer.ipynb` for **week_2**, you will find the final evaluation metrics, tables, and sample translations in the notebook's last section.

- **Training Metrics Table:** For example, at step 87/810, the model reports `loss: 8.7989` and `masked_accuracy: 0.0089`, indicating early-stage learning progress. These metrics help track how well the Transformer is optimizing over time.
- **Sample Translations:** Example input sentences and their translated outputs are provided, demonstrating the model's translation capabilities at this stage.
- **Saved Model Files:** Trained models and outputs are stored in `artifacts/translator/` for further analysis or continued training.

### Suggested Improvements

- **Increase Training Steps:** Extend training epochs or steps to allow the model to converge and improve accuracy.
- **Hyperparameter Tuning:** Experiment with different learning rates, batch sizes, and attention head counts for better performance.
- **Evaluation Metrics:** Add BLEU or ROUGE scores for more comprehensive translation quality assessment.
- **Error Analysis:** Review incorrect translations to identify common failure cases and refine preprocessing or model architecture.

Review these results to evaluate the attention-based NMT model's current performance and compare its outputs to previous approaches.
