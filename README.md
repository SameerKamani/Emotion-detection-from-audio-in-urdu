# Emotion Detection from Urdu Speech

## Overview

This project focuses on detecting emotions from Urdu speech using deep learning techniques. Given the complexity of the Urdu language and the lack of available resources, the goal is to develop a robust model that can accurately classify emotions in Urdu speech. This work has applications in various fields, including mental health and customer service.

## Authors

- **Shayaan Qazi** - Computer Science, Habib University
- **Ikhlaas Ahmed** - Computer Science, Habib University
- **Sameer Kamani** - Computer Science, Habib University

## Abstract

With the increased use of AI, sentiment analysis has grown significantly. This project uses a deep learning-based approach to detect emotions from Urdu speech, leveraging the latest models and an extensive dataset to contribute to the field of sentiment analysis, particularly for Urdu.

## Research Question

The primary research question is:  
**"How can we accurately detect emotions and sentiments in Urdu speech using deep learning?"**

## Methodology

The methodology consists of the following five main steps:

1. **Pre-processing**  
   Enhancing audio features by stretching pitch and duration.
   
2. **Feature Extraction**  
   Using Mel-frequency cepstral coefficients (MFCCs).
   
3. **Splitting Dataset**  
   Dividing data into training, validation, and test sets.
   
4. **Training Model**  
   Employing various models including SVM, CNN, ResNet50, HuBERT, KNN, and Wav2Vec2.0.
   
5. **Predicting Emotion**  
   Evaluating model performance using accuracy, confusion matrix, and learning curves.

## Dataset

The dataset comprises approximately **14,000 audio files** in WAV format, categorized into four emotions:

- **Anger**
- **Happiness**
- **Neutral**
- **Sadness**

The data was sourced from the **SEMOUR+** dataset, featuring recordings from 24 actors.

## Results

The performance of various models was evaluated, with **Wav2Vec2.0** achieving the highest accuracy of **94.5%**. The results indicate that transformer models outperform traditional machine learning and deep learning models in emotion recognition tasks.

## Conclusion

This project demonstrates the effectiveness of deep learning models, particularly transformer-based models like **Wav2Vec2.0**, in detecting emotions from Urdu speech. Future work will focus on refining the model, expanding the dataset, and exploring additional feature extraction methods.

## References

1. S. Latif, "Cross Lingual Speech Emotion Recognition: Urdu vs. Western Languages," 2018.
2. B. B. Al-onazi, "Transformer-Based Multilingual Speech Emotion Recognition Using Data Augmentation and Feature Fusion," *Applied Sciences*, 2022.
3. R. Shaik, "Sentiment Analysis with Word-Based Urdu Speech Recognition," *Journal of Ambient Intelligence and Humanized Computing*, 2021.
4. U. Sehar et al., "Urdu sentiment analysis via multimodal data mining based on deep learning algorithms," *IEEE Access*, 2021.
5. A. Asghar et al., "An Urdu speech corpus for emotion recognition," *PeerJ Computer Science*, 2022.
6. A. Ullah et al., "Threatening language detection from Urdu data with deep sequential model," *PLOS ONE*, 2024.
7. M. Mateen, N. Z. Bawany, "Deep Learning Approach for Detecting Audio Deepfakes in Urdu," *NUML International Journal of Engineering and Computing*, 2023.

