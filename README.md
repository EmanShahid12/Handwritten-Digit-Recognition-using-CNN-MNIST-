# Handwritten Digit Recognition using CNN (MNIST)

##  Project Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

##  Model Architecture
- Conv2D (32 filters)
- MaxPooling
- Conv2D (64 filters)
- MaxPooling
- Conv2D (128 filters)
- MaxPooling
- Dense (128)
- Dropout (0.5)
- Output layer (Softmax)

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

##  How to Run
```bash
pip install -r requirements.txt
python train.py
python evaluate.py
