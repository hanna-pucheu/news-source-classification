# News Source Classification

An end-to-end natural language processing (NLP) project that classifies the source of news headlines using machine learning and transformer-based models.

## Project Overview

This project explores how different machine learning approaches can be used to identify the publication source of a news headline based on textual patterns and language usage.

Our group implemented and compared:
- RoBERTa transformer model
- Logistic Regression baseline + fine-tuned model

The project includes data preprocessing, exploratory analysis, model training, evaluation, and performance comparison.

## Models Used

### RoBERTa
A transformer-based deep learning model fine-tuned for multiclass text classification tasks using news headline data.

### Logistic Regression
A traditional machine learning baseline model used for comparison against the transformer architecture.

## Tools & Libraries

- Python
- pandas
- scikit-learn
- Hugging Face Transformers
- PyTorch
- NumPy
- Jupyter Notebook

## Contributors
- Hanna Pucheu
- Angela Tan
- Tonoya Ahmed

## Repository Contents

``` id="9f7wpz"
├── final_roberta_model.ipynb
├── final_log_reg.ipynb
├── data/
│   ├── og_headlines_output.csv
│   └── new_dataset.csv
├── figures/
└── README.md
