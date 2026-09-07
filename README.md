# Facial-Emotion-Recognition-using-Convolutional-Neural-Networks-Team-project-

A deep learning system developed using TensorFlow and Python to recognize facial emotions from the FER2013 dataset using convolutional neural networks.

## Features

- Facial emotion recognition using CNN-based models
- Comparison between a custom CNN and a VGG19 transfer learning approach
- Online augmentation during training
- Image duplicate detection using image hash comparison
- Handling of an underrepresented Disgust class due to limited samples
- Progressive fine-tuning through layer unfreezing
- Hyperparameter tuning including batch size and learning rate
- Final test accuracy of 65% on the FER2013 test set

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Convolutional Neural Networks (CNN)
- Transfer Learning
- VGG19

## Team Members

- Tran Viet Hung
- Nguyen Quoc An
- Tran Viet Quan

## My Contribution

- Developed and evaluated a custom CNN model for facial emotion recognition, achieving approximately 60% test accuracy.
- Compared the custom CNN with a VGG19 transfer learning model developed by a team member, then selected the VGG19 model for further optimization and fine-tuning.
- Replaced offline augmentation with online augmentation to increase training data variability without creating additional image instances.
- Identified and removed duplicate images using image hash value comparison to improve dataset quality.
- Performed progressive fine-tuning by first unfreezing deeper VGG19 layers and subsequently unfreezing all convolutional blocks, using a smaller learning rate for further training.
- Tuned the batch size and other training parameters to improve model performance.
- Improved test accuracy from approximately 60% to 65% on the FER2013 test set.

## Developed
2026

