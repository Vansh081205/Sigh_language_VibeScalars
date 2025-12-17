<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Language Recognition Using OpenCV</title>
</head>
<body>

    <h1>Sign Language Recognition Using OpenCV</h1>
    <a href="https://opensource.org/licenses/Apache-2.0">
        <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="License">
    </a>

    <hr>

    <h2>Overview</h2>
    <p>
        This project implements a <strong>real-time Sign Language Recognition system</strong> using <strong>OpenCV</strong> and a <strong>Convolutional Neural Network (CNN)</strong>.
        The system captures hand gestures through a webcam, extracts a <strong>Region of Interest (ROI)</strong>, and predicts the corresponding alphabet sign using a trained deep learning model.
    </p>

    <h2>Features</h2>
    <ul>
        <li>Real-time hand gesture recognition</li>
        <li>ROI-based preprocessing using OpenCV</li>
        <li>CNN-based classification</li>
        <li>TensorFlow/Keras implementation</li>
        <li>Optional PyTorch implementation included</li>
        <li>Modular and easy-to-understand code structure</li>
    </ul>

    <h2>Tech Stack</h2>
    <ul>
        <li><strong>Programming Language:</strong> Python</li>
        <li><strong>Computer Vision:</strong> OpenCV</li>
        <li><strong>Deep Learning:</strong> TensorFlow, Keras</li>
        <li><strong>Notebook Environment:</strong> Google Colab</li>
    </ul>

    <h2>Dependencies</h2>
    <p>Install the required dependencies before running the project:</p>
    <pre><code>pip install tensorflow keras opencv-python numpy pillow scikit-image</code></pre>

    <h2>Dataset</h2>
    <p>
        The model is trained using the <strong>Sign Language MNIST Dataset</strong>, which contains grayscale images of hand gestures representing alphabets.
    </p>
    <p>🔗 <strong>Dataset Link:</strong> <a href="https://www.kaggle.com/datamunge/sign-language-mnist">Sign Language MNIST on Kaggle</a></p>

    <h2>Project Structure</h2>
    <pre><code>
Sign-Language-Recognition/
│
├── ROIinOpenCV.py              # Main script for real-time recognition
├── CNNmodel.h5                 # Trained CNN model
├── cnn.py                      # Model training and architecture
├── ASL.ipynb                   # Dataset preprocessing and experiments
├── sign_language_pytorch.ipynb # PyTorch implementation
├── requirements.txt
└── README.md
    </code></pre>

    <h2>How to Run</h2>
    <ol>
        <li>Clone the repository</li>
        <li>Install all required dependencies</li>
        <li>Ensure the trained model file (<code>CNNmodel.h5</code>) is present</li>
        <li>Run the main script:</li>
    </ol>
    <pre><code>python ROIinOpenCV.py</code></pre>
    <p>A webcam window will open and start predicting sign language gestures in real time.</p>

    <h2>PyTorch Implementation</h2>
    <p>
        A PyTorch-based version of the model is provided for experimentation:
    </p>
    <pre><code>sign_language_pytorch.ipynb</code></pre>

    <h2>Results</h2>
    <p>
        The system provides reliable real-time predictions under good lighting conditions.
        ROI-based preprocessing significantly improves classification accuracy and stability.
    </p>

    <h2>Future Improvements</h2>
    <ul>
        <li>Word and sentence-level recognition</li>
        <li>Dynamic gesture support</li>
        <li>Improved background subtraction</li>
        <li>Mobile and web deployment</li>
        <li>Speech synthesis integration</li>
    </ul>

    <h2>License</h2>
    <p>
        This project is licensed under the <strong>Apache License 2.0</strong>.
        See the LICENSE file for more details.
    </p>

</body>
</html>
