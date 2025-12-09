# Sentiment Analysis on Amazon Reviews

[![License:
MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Sentiment classification of Amazon product reviews using RNNs (vanilla
> RNN / Bidirectional LSTM / GRU).\
> A compact demo with a Jupyter notebook, a simple web UI, and reusable
> tokenizer for inference.

------------------------------------------------------------------------

## Table of contents

-   [About](#about)\
-   [Highlights](#highlights)\
-   [Repository structure](#repository-structure)\
-   [Quick start](#quick-start)\
-   [What's inside / How it works](#whats-inside--how-it-works)\
-   [Files you should know](#files-you-should-know)\
-   [How to reproduce results](#how-to-reproduce-results)\
-   [Extend / Improve](#extend--improve)\
-   [Troubleshooting](#troubleshooting)\
-   [License & Citation](#license--citation)\
-   [Contact](#contact)

------------------------------------------------------------------------

## About

This project performs sentiment analysis on Amazon reviews using
sequence models (RNN, BiLSTM, GRU). It includes:

-   A Jupyter notebook that walks through data preprocessing,
    tokenization, model architecture, training and evaluation.
-   `tokenizer.pkl` (pre-fitted tokenizer) for inference.
-   A lightweight `main.py` + `index.html` demo (simple UI to test model
    predictions).
-   MIT license.

------------------------------------------------------------------------

## Highlights

-   Clear end-to-end pipeline: text cleaning → tokenization → sequence
    padding → model training → evaluation → inference.
-   Experiments with vanilla RNN, Bidirectional LSTM and GRU
    architectures.
-   A ready-to-use tokenizer for inference.

------------------------------------------------------------------------

## Repository structure

    .
    ├─ LICENSE
    ├─ README.md
    ├─ Sentiment Analysis with RNN, bidirectional LSTM and GRU.ipynb
    ├─ main.py
    ├─ index.html
    ├─ tokenizer.pkl
    └─ (models, data, outputs)

------------------------------------------------------------------------

## Quick start

### Create environment

    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
    pip install -U pip
    pip install -r requirements.txt

### Run the notebook

    jupyter notebook

### Run the demo app

    python main.py

------------------------------------------------------------------------

## What's inside / How it works

1.  **Preprocessing** -- cleaning, tokenization, padding\
2.  **Tokenizer** -- stored in `tokenizer.pkl`\
3.  **Models** -- RNN, BiLSTM, GRU\
4.  **Evaluation** -- accuracy, F1-score, confusion matrix

------------------------------------------------------------------------

## Files you should know

-   Notebook: full pipeline\
-   `tokenizer.pkl`: tokenizer used for inference\
-   `main.py`: demo backend\
-   `index.html`: simple UI

------------------------------------------------------------------------

## How to reproduce results

1.  Open notebook\
2.  Train RNN/LSTM/GRU\
3.  Save model\
4.  Use tokenizer + model in inference script

------------------------------------------------------------------------

## Extend / Improve

-   Add Dockerfile\
-   Add Streamlit/Gradio UI\
-   Add transformers (BERT, DistilBERT)\
-   Add CI + tests

------------------------------------------------------------------------

## Troubleshooting

-   **Tokenizer mismatch** → ensure same vocab\
-   **Model shape issues** → check padding length\
-   **Slow training** → use GRU or GPU

------------------------------------------------------------------------

## License & Citation

Released under MIT License.

------------------------------------------------------------------------

## Contact

**Manpreet Singh**

Feel free to open issues or suggestions.
