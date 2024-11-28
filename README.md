# **Fake News Detection with NLP**

## **Project Overview**
This project focuses on detecting fake news using various NLP techniques and machine learning models. The goal is to differentiate between real and fake news using datasets and models optimized for accuracy and performance.

---

## **Key Features**
1. **Datasets Used:**
   - **Fake and Real News Dataset (Kaggle):** Processed for binary classification.
   - **FNC-1 Dataset:** Used for multi-class stance classification.
   - **Kaggle Fake News Dataset:** Analyzed with deep learning approaches.

2. **Models Implemented:**
   - **DistilBERT:** Lightweight transformer for sequence classification.
   - **BERT:** Fine-tuned for text classification with high accuracy.
   - **Logistic Regression:** Baseline model with competitive performance.
   - **RNN and LSTM:** Deep learning architectures for binary and multi-class classification.

3. **Techniques Used:**
   - Data preprocessing with tokenization and stemming.
   - Hyperparameter tuning for performance optimization.
   - Fine-tuning transformer models (e.g., NLI-RoBERTa).
   - Handling class imbalance with oversampling techniques.

---

## **Results**
- **Fake and Real News Dataset:**
  - DistilBERT achieved high precision with minimal loss.
  - Logistic Regression performed well as a baseline.
- **FNC-1 Dataset:**
  - DistilBERT and logistic regression struggled due to data complexity.
- **Final Dataset (RNN/LSTM):**
  - Achieved 91.1% accuracy with RNN and LSTM models, leveraging preprocessed data.

---

## **Conclusion**
This project highlights the importance of dataset complexity and preprocessing in fake news detection. While transformer models excel on simpler datasets, deep learning architectures like RNNs and LSTMs deliver competitive results on more complex data.
