# Music Recommendation through Facial Expression

This project is a real-time music recommendation system based on facial expression analysis. It detects the user's emotions through their webcam and recommends music that matches their mood.

## Overview

The project consists of three main components:

1. Data Collection: Utilizes OpenCV and MediaPipe to collect facial landmark data for training the emotion detection model.
2. Data Training: Uses TensorFlow and Keras to train a deep learning model for emotion recognition.
3. Inference and Music Recommendation: Combines the trained model with OpenCV for real-time emotion detection and recommends music based on the detected emotion.

## Requirements

- Python 3.x
- OpenCV
- TensorFlow
- Keras
- MediaPipe

## Usage

1. Run the data collection script to collect facial landmark data:

   python data_collection.py

2. Train the emotion detection model:

   python data_training.py

3. Run the inference script to detect emotions in real-time:

   python inference.py

4. Run the music script to recommend music based on language and singer preference:

   streamlit run music.py
