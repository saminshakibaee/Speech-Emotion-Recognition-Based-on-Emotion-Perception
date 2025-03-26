# Speech-Emotion-Recognition-Based-on-Emotion-Perception

This repository contains the Python implementation of the approach proposed in the paper "Speech Emotion Recognition Based on Emotion Perception" by Gang Liu, Shifang Cai, and Ce Wang. The method is designed to enhance Speech Emotion Recognition (SER) by incorporating emotional perception, inspired by the human brain's emotional processing mechanisms.

# Overview
Speech Emotion Recognition (SER) is a challenging task in speech signal processing, which aims to detect and classify emotions from speech signals. Traditional SER approaches have heavily relied on computer vision and natural language processing techniques, which are not always optimal for emotion extraction. This project introduces a novel approach that combines emotional perception with multi-task learning to improve SER performance.

# Key Features of the Approach:
Emotion Perception: The method mimics the emotional perceptive process of the human brain, creating a more human-like understanding of emotional attributes.

Multi-Task Learning: Implicit emotional information is introduced via multi-task learning to enhance the recognition of emotions.

Improved Performance: Preliminary experiments on the IEMOCAP dataset show improved accuracy with the proposed method. The unweighted accuracy (UA) increased by 2.44%, and the weighted accuracy (WA) increased by 3.18% compared to previous methods.

# Dataset
The method is evaluated on the Interactive Emotional Dyadic Motion Capture (IEMOCAP) dataset, which contains a collection of emotionally expressive speech recordings. You can find more information about the IEMOCAP dataset here.

# Requirements
To run this project, you need to install the following dependencies:

Python 3.x

TensorFlow (for deep learning models)

NumPy

Scikit-learn

librosa (for audio processing)

Matplotlib (for visualization)

# Conclusion
In this project, we have successfully implemented a novel approach to Speech Emotion Recognition (SER) based on emotional perception, inspired by the human brain’s emotional processing. By introducing implicit emotional information through multi-task learning, our method improves the accuracy of emotion classification in speech signals.

The preliminary results on the IEMOCAP dataset demonstrate significant improvements, with a 2.44% increase in unweighted accuracy (UA) and a 3.18% increase in weighted accuracy (WA) compared to existing methods. These findings validate the effectiveness of integrating emotion perception into SER systems, offering a more human-like recognition of emotional attributes in speech.

The approach not only enhances the overall performance of speech emotion recognition models but also opens new avenues for research in emotion-aware speech processing. Future work may focus on refining the model and exploring its potential applications in real-world scenarios, such as human-computer interaction, mental health monitoring, and personalized speech assistants.
