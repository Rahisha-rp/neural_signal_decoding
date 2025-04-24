# Neural Signal Decoding: EEG Motor Imagery Classification

![EEG Signals](https://example.com/eeg_plot.png) *(Example visualization)*

## Overview
This project decodes left/right hand motor imagery from EEG signals using deep learning (CNNs & Transformers). It includes:
- **EEG preprocessing** (filtering, epoching, normalization).
- **CNN & Transformer models** for classification.
- **Training & evaluation scripts**.

## Dataset
- **Source**: [EEG Motor Movement/Imagery Dataset](https://physionet.org/content/eegmmidb/1.0.0/).
- **Files**: `.edf` format (1-110 subjects).

## Installation
```bash
pip install -r requirements.txt  # Install dependencies
