# Multi-Label-Emotion-Recognition-from-Text
Project Title: Multi-Label Emotion Recognition from Text
Description:

In this project, I developed a deep learning-based model for multi-label emotion recognition from textual data using the BERT (Bidirectional Encoder Representations from Transformers) architecture. The objective was to detect multiple emotions (such as joy, sadness, anger, fear, etc.) simultaneously from a given text input, as real-world sentences can express more than one emotion at a time.

Key highlights of the project:

Utilized BERT-base-uncased pretrained model with fine-tuning for multi-label classification.

Implemented BCEWithLogitsLoss with customized pos_weight to effectively handle class imbalance in the dataset.

Achieved an overall accuracy of 90% on the validation set, indicating the model’s strong performance.

Metrics such as precision, recall, and F1-score were used to evaluate the model comprehensively.

Applied sigmoid activation on the output layer to allow multiple emotion predictions per instance.

Dataset preprocessing, tokenization, and training were performed using the Hugging Face Transformers and Datasets libraries.

This project demonstrates the effectiveness of transformer-based models in complex Natural Language Processing (NLP) tasks involving nuanced emotional understanding.
