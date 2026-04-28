# Emotions Dataset for NLP

This repository contains code and resources for working with the **Emotions Dataset for NLP** from Kaggle.

## Dataset Information

- **Source:** [Kaggle: Emotions Dataset for NLP](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
- **Author:** praveengovi
- **Size:** 20,000+ text samples
- **Emotions:** sadness, joy, love, anger, fear, surprise
- **License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

## Dataset Structure

```
train.txt    - Training data (tab-separated: text, emotion)
val.txt      - Validation data
test.txt     - Test data
```

## Getting Started

### 1. Download the Dataset
- Go to [Kaggle Emotions Dataset](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp)
- Download and place files in the `data/` directory

### 2. Install Dependencies
```bash
pip install pandas scikit-learn transformers torch
```

### 3. Run Analysis
```bash
python scripts/load_data.py
```

## Project Structure

```
proj1-1/
├── README.md
├── data/
│   ├── train.txt
│   ├── val.txt
│   └── test.txt
├── scripts/
│   ├── load_data.py
│   └── train_model.py
└── notebooks/
    └── analysis.ipynb
```

## Sample Data Format

```
i didnt feel humiliated	sadness
i can go from feeling so hopeless to so damned hopeful	joy
```

## Use Cases

- Emotion classification models
- Transfer learning with transformers
- Sentiment analysis
- NLP research

## License

Dataset is licensed under CC BY 4.0. See LICENSE file for details.
