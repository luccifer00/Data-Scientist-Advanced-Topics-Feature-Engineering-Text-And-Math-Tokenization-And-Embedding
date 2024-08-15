# Tokenizer and Embedding Notebook

## Project Overview
This notebook is part of a larger project aimed at developing a neural network capable of understanding natural language, LaTeX, and mathematical expressions. The ultimate goal is to enable the network to solve complex mathematical problems. The project is motivated by the Kaggle competition ["Artificial Intelligence Mathematical Olympiad"](https://www.kaggle.com/competitions/ai-mathematical-olympiad-prize). It is divided into four main sections, each focusing on different aspects of data processing and neural network training:

1. **[Data Cleaning and Custom Tokenization](https://github.com/luccifer00/Data-Analyst-Data-Wrangling-Data-Cleaning)**: This section focuses on cleaning and preparing the data, and custom tokenization to extract mathematical expressions.
2. **[Mathematical Expression Parsing](https://github.com/luccifer00/Data-Scientist-Symbolic-Processing)**: This section focuses on parsing the extracted mathematical expressions into a format suitable for analysis.
3. **[Tokenizer and Embedding Notebook](https://github.com/luccifer00/Data-Scientist-Advanced-Topics-Feature-Engineering-Text-And-Math-Tokenization-And-Embedding)**
This section involves creating embeddings and vectorizing the words and the parsed data to prepare it for neural network training.
4. **Neural Network Training**: The final section will involve feeding the processed data into a neural network to enable it to solve complex mathematical problems.

## Project Description
This project focuses on the extraction and processing of mathematical expressions in LaTeX format from specific datasets. The main objective is to prepare and clean these data for subsequent analysis and modeling.

## Notebook Details
The notebook "Tokenizer-and-Embedding-Notebook.ipynb" performs the following tasks:
- Processes a DataFrame containing LaTeX expressions, parsing each cell and extracting relevant variables.
- Tokenizes and lemmatizes the text data.
- Generates embeddings using GloVe, Word2Vec, and BERT models.
- Stores the processed results in a JSON file for further analysis and model training.

## Usage Instructions
To run this notebook, ensure you have the following libraries installed:
- `numpy`
- `pandas`
- `sympy`
- `ast`
- `spacy`
- `gensim`
- `transformers`
- `torch`
- `warnings`

Additionally, for `spacy` and `transformers`, you may need to install specific models. You can install them using the following commands:
```bash
pip install spacy
python -m spacy download en_core_web_sm
pip install transformers