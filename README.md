# ANN-Based Classification of GoEmotions Using Embedding + MLP

## Project Overview
This project focuses on identifying emotions in text using an Artificial Neural Network (ANN). It uses the GoEmotions dataset to classify text into different emotion categories with the help of word embeddings and a Multi-Layer Perceptron (MLP).

## Problem Statement
Understanding emotions from text is challenging because people express their feelings in different ways. This project aims to automatically identify emotions in text using deep learning techniques.

## Dataset
The project uses the GoEmotions dataset from Hugging Face. It contains text comments labeled with 28 emotion categories, including joy, sadness, anger, fear, gratitude, and neutral.

Dataset link: https://huggingface.co/datasets/SetFit/go_emotions

## Objectives
- Preprocess text data for model training.
- Convert words into numerical representations using embeddings.
- Build a baseline ANN model and a proposed MLP model.
- Train and evaluate the models.
- Compare model performance using classification metrics.

## Methodology
1. **Data Preprocessing:** Convert text to lowercase, tokenize words, and prepare sequences of fixed length.
2. **Word Embeddings:** Represent words as numerical vectors using an embedding layer.
3. **Model Building:** Develop baseline and proposed MLP architectures for emotion classification.
4. **Model Training:** Train the models using PyTorch and experiment with different learning rates and batch sizes.
5. **Evaluation:** Compare the models using precision, recall, exact-match accuracy, and F1-score.

## Technologies Used
- Python
- PyTorch
- Hugging Face Datasets
- Google Colab
- NumPy
- Scikit-learn
- Matplotlib

## Results
The proposed MLP model performed better than the baseline ANN in the reported experiments. The comparison showed improvements in precision, recall, and F1-score.

## Future Enhancements
- Improve classification performance for less frequent emotions.
- Experiment with advanced neural network architectures.
- Develop a simple interface for predicting emotions from user-provided text.

## Author
**Shreya Neerati**  
**Roll Number:** 2023006422

## References
- GoEmotions Dataset: https://huggingface.co/datasets/SetFit/go_emotions
- PyTorch Documentation: https://pytorch.org/docs/
