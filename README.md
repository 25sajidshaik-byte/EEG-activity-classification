# EEG-activity-classification
EEG-based activity classification using ML &amp; DL models with different window sizes

# EEG Activity Classification using Machine Learning and Deep Learning

## 📖 Project Overview
This project focuses on classifying human activities using wearable EEG signals and motion sensor data. Both Machine Learning (ML) and Deep Learning (DL) models are implemented and compared.

## 🎯 Objectives
- Classify activity/artifact conditions from EEG signals
- Compare EEG-only vs EEG + motion sensor data
- Evaluate ML (Random Forest, SVM, LightGBM) and DL (CNN, LSTM) models
- Analyse the effect of window sizes on performance

## 📊 Dataset
- Source: Mendeley EEG Dataset
- 12 activity classes (e.g., eye blink, walking, talking, etc.)
- 14 EEG channels + motion sensor data


## ⚙️ Methods
- Data preprocessing & normalization
- Time-series windowing (64, 128, 256)
- Feature engineering for ML models
- Raw signal input for DL models

## 🤖 Models Used
### Machine Learning:
- Random Forest
- Support Vector Machine (SVM)
- LightGBM

### Deep Learning:
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)

## 📈 Results Summary
- CNN performed best in multimodal setting (~0.89 accuracy)
- LightGBM achieved highest ML accuracy (~0.91)
- Multimodal (EEG + Motion) outperformed EEG-only
- Smaller window size (64) gave best performance
- LSTM underperformed due to noisy temporal signals


## 🛠️ Tools & Technologies
- Python
- NumPy, Pandas
- Scikit-learn
- TensorFlow/Keras
- Google Colab

