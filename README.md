# Custom Word2Vec (word embeddings)

<!-- ![Ramayan Pic](https://upload.wikimedia.org/wikipedia/commons/a/a0/Avatars.jpg) -->

<!-- <p align="left">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a0/Avatars.jpg" alt="Ramayan Pic from Wikipedia">
</p> -->

This repository contains the results of a comprehensive analysis of the carious texts. The process involved collecting the PDFs, parsing the document, and extracting the textual data. The data underwent initial manual cleaning for a quick overview, followed by a series of NLP-based text cleaning procedures. And finally training a custom Word2Vec model with CBOW and Skipgram architechure.

## Data Cleaning Steps:

1. **Manual Cleaning:**
   - Initial quick manual cleaning for basic data preprocessing.

2. **NLP-Based Text Cleaning:**
   - Utilized Natural Language Processing (NLP) techniques for advanced text cleaning.
   - Applied techniques such as tokenization, stemming, and lemmatization to enhance data quality.

## Word2Vec Model Building:

- Employed the `textract/gensim` library to build Word2Vec models.
- Two variations of the model were created:
   1. Continuous Bag of Words (CBOW) Method
   2. Skip-gram Method

## Data Visualization:

- Conducted visualizations of the raw text data and its corresponding vectors in both 2D and 3D spaces.
- Utilized Principal Component Analysis (PCA) for dimensionality reduction in vector data visualization.

## Repository Structure:

- `data/`: Contains the collected Ramayan PDF and cleaned text data.
- `assets/`: Includes the saved CBOW and Skip-gram Word2Vec models.
- `visualizations/`: Holds the visual representations of raw text and vector data.

## Instructions for Usage:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ramayan-nlp.git
   cd ramayan-nlp
