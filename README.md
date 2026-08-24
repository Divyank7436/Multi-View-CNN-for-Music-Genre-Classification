# Multi-View CNN for Music Genre Classification

A deep learning project for **16-class music genre classification** using RGB mel-spectrogram representations and a custom multi-view CNN architecture.

## Features

- Multi-view CNN for processing three spectrogram representations
- Pairwise feature interaction and fusion
- SpecAugment and scheduled Mixup augmentation
- Class-balanced training using weighted sampling
- AdamW optimizer with learning-rate scheduling
- Mixed-precision training and EMA
- Evaluation using Accuracy, Precision, Recall and Macro-F1

## Results

The final optimized model achieved a **Validation Macro-F1 score of 0.934**.

## Tech Stack

**Python, PyTorch, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn**

## Dataset

Music genre dataset provided through the **CS-776 competition environment**.

## Project Structure

```text
Multi-View-CNN-Music-Genre-Classification/
├── Multi_View_CNN_Music_Genre_Classification.ipynb
└── README.md
