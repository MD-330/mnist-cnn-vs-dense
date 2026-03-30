<img width="1717" height="707" alt="image" src="https://github.com/user-attachments/assets/7f9416cc-20c0-46ef-90a2-07f47af64ef5" /># mnist-cnn-vs-dense
Deep learning project using TensorFlow for handwritten digit classification (MNIST), comparing Dense and CNN models with performance evaluation.
🧠 MNIST CNN vs Dense

A deep learning project using TensorFlow to classify handwritten digits (MNIST), comparing a simple Dense neural network with a CNN model.

📌 Project Overview

This project demonstrates:

Loading and preprocessing data using TensorFlow Datasets
Training two different models:
Dense (Fully Connected Neural Network)
Convolutional Neural Network (CNN)
Comparing performance between the two approaches
⚙️ Technologies Used
Python
TensorFlow / Keras
TensorFlow Datasets
Google Colab
🧪 Models
🔹 Model 1: Dense Neural Network
Flatten layer
Dense(128, ReLU)
Dense(10)
🔹 Model 2: CNN
Conv2D + ReLU
MaxPooling
Conv2D + ReLU
MaxPooling
Flatten
Dense(128, ReLU)
Dense(10)
📊 Results
Model	Train Accuracy	Validation Accuracy
Dense	~98.5%	~97.5%
CNN	~99.0%	~98.8%
📈 Analysis
CNN achieved better performance than the Dense model
The improvement is noticeable but not very large
CNN is more suitable for image data because it captures spatial features (edges, shapes)
💡 Conclusion
Dense model works well for simple tasks
CNN provides better generalization for image classification
Even small architectural changes can improve model performance
🚀 Future Improvements
Test different CNN architectures
Tune hyperparameters (epochs, batch size)
Apply data augmentation
Deploy the model in a simple web app
