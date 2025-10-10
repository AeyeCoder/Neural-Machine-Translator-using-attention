Transformer Translation Model

A simple implementation of a Transformer-based sequence-to-sequence translation model using TensorFlow and Keras.

Overview

This project demonstrates how attention-based Transformers can learn to translate sentences from one language to another. It includes tokenization, positional encoding, masking, encoder-decoder architecture, and inference translation functions.

Features

Custom tokenization and vectorization layers

Encoder-decoder attention mechanism

Training with sparse_categorical_crossentropy loss

Inference loop for sentence translation

Usage

Preprocess your text data.

Train the model using the provided model.fit() setup.

Use the translate() function to generate translations for new input sentences.
