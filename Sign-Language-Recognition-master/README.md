# Sign Language Recognition Using OpenCV

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

---

## Overview
This project implements a **real-time Sign Language Recognition system** using **OpenCV** and a **Convolutional Neural Network (CNN)**. The system captures hand gestures from a webcam feed, processes a **Region of Interest (ROI)**, and predicts the corresponding alphabet sign using a deep learning model.

---

## Features
- Real-time hand gesture recognition with a webcam
- ROI-based preprocessing using OpenCV
- CNN-based classification with TensorFlow/Keras
- Additional PyTorch implementation available
- Modular and well-organized codebase

---

## Tech Stack
- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Deep Learning:** TensorFlow, Keras
- **Notebook Environment:** Google Colab

---

## Dependencies
Install the required dependencies before running the project:

```bash
pip install tensorflow keras opencv-python numpy pillow scikit-image

## Dataset
The model is trained using the Sign Language MNIST Dataset, which contains grayscale images of hand gestures representing the alphabet letters.

##Dataset Link: Sign Language MNIST on Kaggle



##Project Structure
Sign-Language-Recognition/
│
├── ROIinOpenCV.py              # Main script for real-time recognition
├── CNNmodel.h5                 # Trained CNN model file
├── cnn.py                      # Model training and architecture script
├── ASL.ipynb                   # Dataset preprocessing and exploration notebook
├── sign_language_pytorch.ipynb # PyTorch version of the implementation
├── requirements.txt
└── README.md


How to Run

Clone the repository.
Install all required dependencies.
Ensure the trained model file (CNNmodel.h5) is in the correct directory.

Run the main script:
python ROIinOpenCV.py

A webcam window will open, and the system will start predicting sign language gestures in real time.

PyTorch Implementation

A PyTorch-based implementation is also provided in the sign_language_pytorch.ipynb notebook for further experimentation.

Results

The system delivers reliable real-time predictions under good lighting conditions. Using ROI-based preprocessing improves accuracy and stability significantly.

Future Improvements

Support for recognizing full words and sentences

Dynamic gesture recognition

Enhanced background subtraction

Deployment on mobile platforms

Integration with speech synthesis

License
This project is licensed under the Apache License 2.0. See the LICENSE file for more details.
---
With this complete Markdown README, you can now paste it directly into your `README.md` file, and it will r

