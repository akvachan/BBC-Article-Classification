# BBC-Article-Classification
BBC Article Classification and Visualisation using Embeddings and Dense Neural Network

## Overview
This project demonstrates the use of TensorFlow to classify BBC news articles into predefined categories. Utilizing a dataset of BBC articles, the project employs natural language processing techniques, including tokenization and stopwords removal, to prepare the data. A neural network model is then built and trained to categorize new articles accurately.

## Features
- Preprocessing of text data to remove common English stopwords.
- Tokenization and sequence padding to convert text into a format suitable for neural network training.
- A neural network model with an embedding layer, a dense layer with ReLU activation, and a softmax output layer for multi-class classification.
- Evaluation of model performance through accuracy and loss metrics.
- Visualization of training process and word embeddings.

## Project Structure
bbc-article-classification/
bbc-text.csv - Dataset file containing the BBC articles and their labels.
bbc_article_classification.ipynb - Jupyter notebook with the project's code.
vecs.tsv - Output file containing word vectors for visualization.
meta.tsv - Output file containing metadata for word vectors.
README.md - This file.


## Getting Started

### Prerequisites
- Python 3.6 or later
- TensorFlow 2.x
- NumPy
- Matplotlib

### Installation
1. Clone the repository:
git clone https://github.com/yourusername/bbc-article-classification.git

2. Install the required packages:
pip install tensorflow numpy matplotlib

### Usage
To run the project, open the `bbc_article_classification.ipynb` notebook in Jupyter Lab or Google Colab and execute the cells sequentially.

## Contributing
Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Dataset from [BBC](http://mlg.ucd.ie/datasets/bbc.html) for research purposes.
- TensorFlow for providing the tools to build and train the model.
