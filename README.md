# Fake News Detection

## Overview
This project detects fake news articles using machine learning. It processes textual data to classify news as real or fake.

## Features
- Preprocessing of news articles (stopword removal, tokenization, etc.)
- Feature extraction using TF-IDF
- Machine learning classification using Logistic Regression
- Evaluation of model performance

## Installation
### Prerequisites
Ensure you have Python installed along with necessary dependencies:
```bash
pip install -r requirements.txt
```

## Dataset
The dataset contains two files:
- `Fake.csv` - Fake news articles
- `True.csv` - Real news articles

These files were used for training and testing. If the dataset is too large, download it from [Kaggle](https://www.kaggle.com/c/fake-news) and place it in the `data/` directory.

## Usage
To run the project:
1. Clone the repository:
   ```bash
   git clone https://github.com/Vidushi9950/Fake-News-Detection/tree/main
   cd fake-news-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `fake_news_detection.ipynb` and execute the cells.

## Model and Methodology
The project follows these steps:
1. **Data Preprocessing**: Cleaning and preparing text data.
2. **Feature Extraction**: Using TF-IDF vectorization.
3. **Model Training**: Logistic Regression classifier.
4. **Evaluation**: Accuracy measurement and classification report.

## Results
- **Model Accuracy:** 98.64%


