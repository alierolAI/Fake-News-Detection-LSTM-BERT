# Fake News Detection with LSTM and BERT

This project focuses on fake news classification using both traditional deep learning and transformer-based NLP approaches.  
An LSTM baseline model and a fine-tuned BERT model were implemented and compared on a real-world fake news dataset.  
The project also includes attention visualization to analyze which words the transformer model focuses on during classification.

Technologies used:
- TensorFlow / Keras
- Hugging Face Transformers
- BERT Fine-Tuning
- LSTM Networks
- Attention Visualization
- NLP Preprocessing
- Scikit-learn

## Features
- End-to-end NLP pipeline for fake news classification
- Text preprocessing and cleaning
- Tokenization and sequence encoding
- Sequence padding for deep learning models
- LSTM-based fake news classification
- Fine-tuned BERT transformer model
- Real-world external news inference
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
- Comparison between LSTM and BERT architectures
- Attention visualization for explainable AI (XAI)
- Trained model saving and reusable inference pipeline

##Dataset
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

##RESULTS
LSTM-Results
<img width="1772" height="1427" alt="lstm_confusion_matrix" src="https://github.com/user-attachments/assets/3e0d67d2-c3fc-4185-8de1-53755776f66a" />

<img width="3194" height="881" alt="lstm_classification_report" src="https://github.com/user-attachments/assets/837b2d39-bbc5-4c2a-b722-2db35e15b4da" />

<img width="2400" height="1500" alt="lstm_external_test_result" src="https://github.com/user-attachments/assets/2ec78372-c8f7-440f-b07f-07e66a4eca31" />

##Future improvements
- Fine-tuned BERT
- Attention visualization
- Streamlit UI
- REST API
