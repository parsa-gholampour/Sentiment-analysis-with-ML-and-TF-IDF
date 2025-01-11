# Sentiment Analysis with Machine Learning

This repository provides a comprehensive workflow for sentiment analysis using text data. The notebook leverages machine learning techniques to classify text as positive or negative.

## Features

- **Data Handling**:
  - Functions to load and preprocess data.
  - Capability to handle datasets with multiple labels (e.g., positive and negative).
- **Text Preprocessing**:
  - Removal of stopwords.
  - Lemmatization for improved generalization.
  - TF-IDF vectorization for feature extraction.
- **Model Training**:
  - Uses logistic regression for classification.
  - Splits data into training and testing subsets for evaluation.
- **Performance Evaluation**:
  - Provides metrics to assess the classifier's accuracy and effectiveness.

## Requirements

The following libraries are required to run the notebook:

- Python 3.7+
- pandas
- nltk
- scikit-learn

## Usage

1. Prepare your data:
   - Place your text data in a folder structure with subfolders for each label (e.g., `pos` and `neg`).
2. Run the notebook:
   ```bash
   jupyter notebook source.ipynb
   ```
3. Follow the instructions in the notebook to load data, preprocess text, train the model, and evaluate performance.

## Dataset

The notebook is designed to work with datasets like IMDB movie reviews. Ensure the dataset follows a directory structure with separate folders for each class label.

Link: https://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz

## Results

The notebook outputs metrics such as accuracy and confusion matrix to evaluate the performance of the logistic regression model.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests with improvements or suggestions.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.


