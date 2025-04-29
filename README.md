# Neural Machine Translation with Attention

This repository contains the programming assignment from **Week 3** of **Course 5: Sequence Models** in the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) by Andrew Ng on Coursera.

## Overview

In this assignment, a sequence-to-sequence (seq2seq) model with attention is implemented to perform English-to-French translation. The model demonstrates how attention mechanisms improve performance by helping the decoder focus on relevant parts of the input sentence during translation.

Key concepts covered:
- Sequence-to-sequence architecture
- Bidirectional LSTM encoder
- Attention mechanism for alignment
- Decoder with context vector integration
- Translation generation from input sequences

This task is a practical application of deep learning in natural language processing (NLP), especially in machine translation.

## Contents

- `preprocess_data()` – Cleans and tokenizes input text
- `NMT_AttentionModel()` – Constructs the encoder-decoder model with attention
- `train_model()` – Compiles and fits the model on paired training data
- `translate()` – Uses the trained model to translate English sentences into French
- Jupyter Notebook – Walkthrough of implementation, training, and testing

## Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy

## Course Information

- Course: Sequence Models (Course 5 of 5)
- Specialization: Deep Learning Specialization
- Instructor: Andrew Ng
- Platform: Coursera
- Institution: DeepLearning.AI

## License

This repository is based on educational material provided by DeepLearning.AI through Coursera. It is intended for academic and personal use only. Redistribution for commercial purposes is prohibited.

---
