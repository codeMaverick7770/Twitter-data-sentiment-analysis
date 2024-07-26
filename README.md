![Uploading image.png…]()
# Sentiment Analysis using NLP

This repository contains a project focused on Sentiment Analysis using Natural Language Processing (NLP) techniques. The project utilizes the Sentiment140 dataset, which includes 1.6 million labeled tweets, to train a model for classifying sentiments.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

Natural Language Processing (NLP) is a field of Artificial Intelligence that enables machines to understand and process human languages. In this project, we focus on text classification to perform Sentiment Analysis, categorizing tweets into Positive and Negative sentiments. Sentiment Analysis is widely used in various industries to gauge public opinion about products, services, or topics.

## Dataset

The project uses the Sentiment140 dataset, which contains 1.6 million labeled tweets. Each tweet is labeled as either Positive (4) or Negative (0).

## Installation

To run this project, you need to have Python installed. Follow the steps below to set up the environment:

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/sentiment-analysis-nlp.git
    ```
2. Navigate to the project directory:
    ```sh
    cd sentiment-analysis-nlp
    ```
3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Download the Sentiment140 dataset and place it in the `data` directory.
2. Run the Jupyter Notebook:
    ```sh
    jupyter notebook sentiment_analysis.ipynb
    ```

## Preprocessing

The preprocessing steps include:
- Removing user mentions, hyperlinks, and non-alphanumeric characters.
- Converting text to lowercase.
- Removing stopwords using NLTK.
- Stemming words using SnowballStemmer.

## Model Training

The project uses TensorFlow for training the sentiment classification model. Key steps include:
- Tokenization of text data.
- Padding sequences to ensure uniform input length.
- Using pre-trained GloVe embeddings for word representation.
- Training a sequence model (e.g., LSTM or GRU).

## Evaluation

The dataset is split into training (80%) and testing (20%) sets. The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Results

The model achieves an accuracy of approximately XX% on the test set. Visualizations of word clouds for Positive and Negative sentiments are also provided.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)
- [NLTK: Natural Language Toolkit](https://www.nltk.org/)
- [TensorFlow](https://www.tensorflow.org/)
- This project is a part of my training in AI/ML from Internz Learn. Thanks to them for their guidance and support.

---

Feel free to reach out if you have any questions or suggestions. Happy coding!
