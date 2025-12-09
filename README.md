# Sentiment Analysis on Amazon Reviews

[![License:
MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Sentiment classification of Amazon product reviews using RNNs (vanilla
> RNN / Bidirectional LSTM / GRU).\
> A compact demo with a Jupyter notebook, a simple web UI, and reusable
> tokenizer for inference.

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

## Demo Video

👉 **[Watch the Demo](https://drive.google.com/file/d/1vix-MS7iSc_ecDmxWiHFyOdSPnPkE5mf/view?usp=sharing)**  

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
    └─ Dataset Download.txt

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


## License

Released under MIT License.

------------------------------------------------------------------------

## Author

**Manpreet Singh**
B.Sc. Artificial Intelligence and Data Science
