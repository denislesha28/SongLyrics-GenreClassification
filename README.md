# Project
This repository contains a comprehensive Jupyter notebook, `nlp_song-lyrics_analysis.ipynb`, which provides an end-to-end NLP workflow. The notebook is structured to analyse and breakdown different methods and possibilities of classifying song lyrics based on genre.
## Notebook Workflow

1. **Data Loading and Exploration**:
   - Load the dataset(s) and perform initial exploration to understand the structure and key features.
   - Visualize data distributions and perform basic statistical analysis.

2. **Data Preprocessing**:
   - Clean and preprocess text data using techniques like:
     - Lowercasing, removing punctuation, and stop word removal
     - Tokenization, stemming, and lemmatization
   - Prepare the data for feature extraction and modeling.

3. **Feature Engineering**:
   - Implement text vectorization methods such as:
     - Bag-of-Words (BoW)
     - Term Frequency-Inverse Document Frequency (TF-IDF)
     - Word embeddings using pre-trained models like Word2Vec or GloVe

4. **Model Building**:
   - Train various NLP models, including:
     - Traditional machine learning models (e.g., Logistic Regression, SVM)
     - Deep learning models using `torch` for text classification
     - Transfer learning with pre-trained transformers from the `transformers` library

5. **Model Evaluation**:
   - Evaluate model performance using metrics such as:
     - Accuracy, precision, recall, and F1-score
     - Confusion matrix analysis
   - Compare different models and discuss their strengths and limitations.

6. **Model Optimization**:
   - Fine-tune models by adjusting hyperparameters
   - Experiment with different architectures or feature extraction techniques to improve performance

7. **Results and Conclusions**:
   - Summarize key findings and model performance
   - Discuss potential areas for improvement and future work

## Notebook Contents

- **Introduction**: Overview of the NLP tasks and project objectives
- **Data Loading & Exploration**: Code and visualizations for understanding the dataset
- **Preprocessing**: Functions and techniques to clean and prepare text data
- **Feature Extraction**: Implementation of various text representation methods
- **Model Training**: Step-by-step guide to building and training machine learning and deep learning models
- **Evaluation & Comparison**: Metrics and analysis to compare model performance
- **Conclusion**: Summary of results and insights gained from the workflow

## How to Use
The notebook was developed in kaggle so paths to dataset and some libraries might need to be adjusted for local execution
## Dataset
[Kaggle dataset](https://www.kaggle.com/datasets/ai23m017/dataset/data) 
