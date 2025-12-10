# toxic-comment-classification

This repository contains two notebooks demonstrating the differences between Naive Bayes and Bidirectional GRU for toxic comment classification.

## Data

The project uses the **Jigsaw Toxic Comment Classification Challenge** dataset from Kaggle.

  * **Source**: [Kaggle Competition Data](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data)
  * **Setup**: Place `train.csv` and `test.csv` in the `data/` directory.

For the Deep Learning model, I used pre-trained **GloVe embeddings** (100d).

  * **Source**: [GloVe 6B 100d on Kaggle](https://www.kaggle.com/datasets/danielwillgeorge/glove6b100dtxt)
  * **Setup**: Place `glove.6B.100d.txt` in the `data/` directory.

## Models

The trained Bidirectional GRU model is hosted on Hugging Face:

  * [freref/toxic\_comments](https://huggingface.co/freref/toxic_comments/tree/main)

## Installation

This project is initialized with **uv**. To install the required dependencies:

```bash
uv sync
```
