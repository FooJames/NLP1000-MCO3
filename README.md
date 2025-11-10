# NLP1000-MCO3
# Project 3: Machine Translation for Yami using Multilingual Data Augmentation

This repository contains the full implementation, data, and analysis for **NLP1000 Project 3**, which focuses on building and evaluating machine translation (MT) models for **Yami**, a low-resource Philippine language. The project explores the effects of **cross-lingual data augmentation** and **multilingual fine-tuning** using related Philippine languages: **Tagalog, Cebuano, Maranao,** and **Hiligaynon**.

---

## Overview

Yami is a low-resource Austronesian language with limited parallel data available for training modern neural machine translation (NMT) models. This project investigates whether augmenting Yami translation with data from related Philippine languages can improve performance.

Using the **MarianMT** architecture from Hugging Face’s **Transformers** library, several multilingual translation systems were fine-tuned on various combinations of Tagalog, Cebuano, Maranao, and Hiligaynon data.

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/nlp1000-project3-yami.git
   cd nlp1000-project3-yami
   ```

2. Create and activate a virtual environment:

   ```bash
   conda create -n nlp_proj3 python=3.10
   conda activate nlp_proj3
   ```

3. Install dependencies:

   ```bash
   pip install -U transformers datasets sacrebleu sentencepiece torch pandas matplotlib scikit-learn accelerate
   ```

4. Open and run the Jupyter notebook:

   ```bash
   jupyter notebook
   ```

5. Run each notebook cell to train and evaluate models. BLEU scores and prediction files will be automatically saved under `artifacts_*` directories.

---
