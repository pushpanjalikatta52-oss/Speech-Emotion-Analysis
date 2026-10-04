# Speech-Emotion-Analysis
# 🎙️ Speech Emotion Analysis Using AI

## 📌 Overview

The **Speech Emotion Analysis System** is an AI-based application that analyzes human speech and predicts the emotional characteristics present in the audio. The system uses a pre-trained **Wav2Vec2** speech model to process audio and classify the detected emotion.

The application provides a simple **Gradio web interface** where users can upload an audio file or record their voice using a microphone.

## 🎯 Objectives

* To analyze emotions from human speech.
* To understand the basics of Speech Emotion Recognition.
* To use a pre-trained Wav2Vec2 model.
* To display emotion prediction with confidence scores.
* To create an easy-to-use AI application using Gradio.
* To run the project directly in Google Colab.

## 🛠️ Technologies Used

* **Python**
* **PyTorch**
* **Wav2Vec2**
* **Hugging Face Transformers**
* **Librosa**
* **Gradio**
* **Google Colab**

## ⚙️ How It Works

1. The user uploads an audio file or records speech.
2. The audio is loaded and converted to the required sampling rate.
3. The Wav2Vec2 model processes the speech signal.
4. The model calculates probabilities for different emotion classes.
5. The emotion with the highest probability is selected.
6. The application displays the predicted emotion and confidence score.

