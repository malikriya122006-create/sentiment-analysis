# Sentiment Analysis using DistilBERT

## Overview
This project focuses on building a sentiment analysis model using DistilBERT to classify movie reviews as positive or negative.

The model is trained and evaluated using the IMDb movie review dataset from Hugging Face.

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Pandas
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load the IMDb dataset.
2. Explore and preprocess the movie reviews.
3. Tokenize text using the DistilBERT tokenizer.
4. Fine-tune the DistilBERT model for sentiment classification.
5. Evaluate model performance.
6. Save the trained model and results.

## Project Structure
```text
sentiment_analysis_project/
├── results/
├── sentiment_model/
├── sentiment_analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Dataset
IMDb Movie Reviews dataset (`stanfordnlp/imdb`), containing positive and negative movie reviews.

## Future Improvements
- Build a web application for real-time sentiment prediction.
- Deploy the model using FastAPI or Streamlit.
