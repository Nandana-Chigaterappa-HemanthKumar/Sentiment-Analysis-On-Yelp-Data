# Sentiment-Analysis-On-Yelp-Data

## 📌 Overview
This project focuses on Sentiment Analysis, a Natural Language Processing (NLP) task that identifies and classifies opinions expressed in text as positive or negative.  
The Yelp Review Dataset was used to train, validate, and evaluate multiple deep learning models, comparing their performance across key metrics such as accuracy, precision, recall, and F1-score.

The pipeline includes comprehensive text preprocessing, data transformation, and fine-tuning of four models:  
BERT, DistilBERT, XLNet, and LSTM.


## Features
* Binary Sentiment Classification (Positive / Negative).
* Text Preprocessing Pipeline:  
  - Lowercasing, stopword & punctuation removal.
  - Lemmatization, URL and HTML tag removal.
  - Contraction expansion and repeated character normalization.
* Model Training & Evaluation.
* Evaluation Metrics: Accuracy, Precision, Recall, F1-Score.

## Tech Stack
* Languages & Frameworks: Python, PyTorch, Transformers (Hugging Face).
* Libraries: Scikit-learn, Pandas, NumPy, TQDM.
* Environment: Jupyter Notebook.
* Dataset: Yelp Review Dataset (transformed to binary sentiment labels).

## Project Structure
```text
├── BERT/ 
├── DistilBERT/
├── XLNet/ 
├── LSTM/ 
├── Data Preprocessing/
└── README.md # Project documentation
```

## License
**This project is for academic use only.**
