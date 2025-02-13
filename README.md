# Disaster-Tweet-Classification
## Open in Google Colab 🚀
Use The Free GPU to Run,
Click the link below to open and run this project in Google Colab:
[Open in Colab](https://colab.research.google.com/)

## Introduction
This project focuses on classifying tweets as disaster-related or not using Natural Language Processing (NLP) and deep learning techniques. The goal is to enhance the efficiency of identifying critical information in social media posts for emergency response teams. The study implements various machine learning and deep learning models to evaluate their effectiveness in tweet classification.

## Project Workflow
### 1. Data Preprocessing
To improve classification accuracy, the following preprocessing steps were applied:
- **Text Cleaning:** Removed special characters, punctuation, numbers, and URLs.
- **Tokenization:** Converted text into individual tokens.
- **Stopword Removal:** Eliminated non-essential words.
- **Lemmatization:** Reduced words to their root forms.
- **Padding Sequences:** Standardized input length.
- **Feature Engineering:** Introduced alarming word counts as an additional feature.

### 2. Machine Learning Model
Initially, various machine learning algorithms were applied in the machine learning model to determine their effectiveness. The results provided insights into feature importance and baseline accuracy for tweet classification.

### 3. Deep Learning Model
A deep learning model was developed using Feedforward Neural Network with the following layers:
- **Embedding Layer:** Converts words into vector representations.
- **GlobalAveragePooling1D Layer:** Reduces dimensionality while preserving key features.
- **Dense Layers with ReLU Activation:** Enhances feature learning.
- **Dropout Layers:** Mitigates overfitting.
- **Sigmoid Output Layer:** Outputs a probability score for classification.

### 4. Hyperparameter Tuning
Hyperparameter tuning was performed to optimize performance, adjusting parameters such as:
- Embedding dimension
- Number of neurons per layer
- Learning rate
- Dropout rate

### 5. BERT-based Pre-trained Model
To further improve classification accuracy, the same dataset was processed using a pre-trained BERT model. This approach leverages transfer learning for better contextual understanding and performance comparison with the deep learning model.

## Model Evaluation
Performance was assessed using:
- **Accuracy:** Measures correct classifications.
- **Precision & Recall:** Evaluates model effectiveness in identifying disaster tweets.
- **F1 Score:** Balances precision and recall.
- **Confusion Matrix:** Analyzes misclassifications.

## Challenges and Solutions
- **Data Quality Issues:** High null values in some columns were addressed by removing less relevant features.
- **Overfitting:** Managed using dropout layers and L2 regularization.
- **Interpretability:** Word clouds and confusion matrices were used to analyze misclassified tweets.

## Conclusion and Future Work
This project successfully implemented machine learning and deep learning techniques for disaster tweet classification. Future improvements could include:
- **Enhancing BERT-based model performance** with fine-tuning.
- **Incorporating attention mechanisms** to improve interpretability.
- **Deploying real-time tweet classification systems** for emergency monitoring.

This research contributes to the development of scalable NLP solutions for crisis management and disaster response.

