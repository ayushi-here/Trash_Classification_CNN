# 🗑️ Trash Classification using CNN | Organic vs Recyclable
This project aims to classify waste images into two categories: Organic and Recyclable using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

# 🔍 Overview
The model is trained on the Waste Classification Dataset from Kaggle. It automatically learns features from images to help in proper waste segregation, which is a small step toward a cleaner and more sustainable environment.

# 📁 Dataset
Sourced from: Kaggle - techsash/waste-classification-data

Classes: Organic, Recyclable

Preprocessing: Resizing to (224x224), normalization, RGB conversion

# 🧠 Model Architecture
A custom CNN built using:

3 Convolutional Layers + MaxPooling

Flatten → Dense Layers with ReLU activation

Dropout layers to reduce overfitting

Final Dense layer with sigmoid activation

# 📈 Training Details
Loss Function: binary_crossentropy

Optimizer: Adam

Epochs: 5

Accuracy visualized with matplotlib

# 🚀 Deployment
The trained model is deployed using Gradio, offering a simple web interface to upload and classify images as:

♻️ Recyclable

🌱 Organic

# 🛠️ Tools Used
Python

TensorFlow/Keras

OpenCV

Gradio

Matplotlib

Pandas, NumPy
