```md
# Financial Market News Sentiment Analysis

This repository contains code for sentiment analysis of financial market news articles using a Random Forest Classifier. The dataset used in this project consists of financial news articles from various sources, along with labels indicating whether the sentiment of the article is positive or negative.

## Overview
In this project, we delve into the realm of data science by exploring the sentiment behind financial market news. Understanding the sentiment of news articles related to financial markets can provide valuable insights for investors, traders, and analysts. By analyzing news sentiment, we aim to uncover patterns, sentiments, and trends that may impact financial markets.

## Objective
The primary objective of this project is to develop a model that can accurately analyze the sentiment of financial market news articles. By leveraging natural language processing (NLP) techniques and machine learning algorithms, we seek to classify news articles into positive, negative, or neutral sentiments. Additionally, we aim to provide visualizations and insights to aid in understanding the sentiment trends over time.

## Key Features
  - Sentiment Analysis: Utilizing NLP techniques to classify the sentiment of financial market news articles.
  - Machine Learning: Employing machine learning algorithms such as classification models to predict sentiment.
  - Data Visualization: Generating visualizations to present sentiment trends and patterns.

## Dataset

The dataset used in this project is available at the following link: [Financial Market News Dataset](https://github.com/ybifoundation/Dataset/raw/main/Financial%20Market%20News.csv)

The dataset contains the following columns:

- `Date`: The date on which the news article was published.
- `Label`: A binary label indicating whether the sentiment of the article is positive (1) or negative (0).
- `News 1` - `News 25`: The text content of the news articles.

## Code

The code for this project is contained in the `Akhya_Financial_Market_News_Sentiment_Analysis.ipynb` Jupyter Notebook. The notebook contains the following steps:

1. **Data Loading**: The dataset is loaded into a pandas DataFrame.
2. **Feature Engineering**: The text content of the news articles is concatenated into a single feature column.
3. **Text Preprocessing**: The text data is converted into a bag-of-words representation using scikit-learn's `CountVectorizer`.
4. **Train-Test Split**: The dataset is split into training and testing sets.
5. **Model Training**: A Random Forest Classifier is trained on the training data.
6. **Model Evaluation**: The performance of the trained model is evaluated on the test data using metrics such as accuracy, precision, recall, and F1-score.

## Requirements

To run the code in this repository, you will need the following packages:

- pandas
- numpy
- scikit-learn

You can install these packages using pip:

```
pip install pandas numpy scikit-learn
```

## Usage

1. Clone the repository to your local machine.
2. Navigate to the repository directory.
3. Open the `Akhya_Financial_Market_News_Sentiment_Analysis.ipynb` notebook in Jupyter Notebook or JupyterLab.
4. Run the notebook cells to load the data, preprocess the text, train the model, and evaluate its performance.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

```
