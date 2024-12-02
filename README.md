Persian Emotion Classification Using BERT
Overview
This project implements Persian emotion classification using a fine-tuned BERT model on a dataset derived from Persian tweets. The model categorizes texts into the following emotions:

Fear
Surprise
Laughter
Sadness
Happiness
Anger
Questioning
Neutral

The model achieves an F1 score of 0.79, demonstrating strong performance in detecting nuanced emotions in Persian text.

Features
Built using the PyTorch deep learning framework.
Leverages a pretrained Persian BERT model for transfer learning.
Fine-tuned for the unique characteristics of the Persian language and emotional contexts.
Dataset
The dataset was constructed from Persian tweets, labeled with corresponding emotions.
Preprocessing steps included tokenization, cleaning, and formatting for compatibility with the BERT tokenizer.
Example:
Input: "امروز خیلی خوشحالم!"
Output: Happiness
Results
Achieved an F1 score of 0.79 on the test dataset.
Confusion matrix and additional evaluation metrics are included in the notebook.
