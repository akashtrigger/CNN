<!-- Handwritten Digit Recognition using CNN -->

A Deep Learning project that uses a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset.
The model is built using TensorFlow and Keras and achieves high accuracy in digit classification.

<!-- 📌 Project Overview -->

This project trains a CNN model to classify handwritten digits (0–9) from grayscale images of size 28×28 pixels.
The dataset used is the famous MNIST dataset, which contains thousands of handwritten digit images.

<!-- 🚀 Technologies Used -->
Python
TensorFlow
Keras
NumPy
Matplotlib
Scikit-learn
Seaborn
<!-- 📂 Dataset -->

The project uses the MNIST Handwritten Digits Dataset available directly from Keras.

Training Images: 60,000
Testing Images: 10,000
Image Size: 28×28 pixels
🧠 CNN Architecture

<!-- The CNN model consists of: -->

Convolution Layer (32 filters)
Max Pooling Layer
Convolution Layer (64 filters)
Max Pooling Layer
Flatten Layer
Dense Layer (64 neurons)
Output Layer (10 neurons with Softmax activation)

<!-- ⚙️ Features -->
Image normalization
CNN model training
Accuracy and loss visualization
Prediction on test images
Confusion matrix evaluation
Handwritten digit classification
<!-- 📊 Model Performance -->

The model is trained using:

Optimizer: Adam
Loss Function: Sparse Categorical Crossentropy
Epochs: 5

The trained model achieves high accuracy on the MNIST test dataset.

<!-- 📈 Visualizations Included -->
Digit image display
Training vs Validation Accuracy Graph
Training vs Validation Loss Graph
Confusion Matrix
<!-- ▶️ How to Run -->
Install required libraries:
pip install tensorflow matplotlib numpy seaborn scikit-learn
Run the Jupyter Notebook:
jupyter notebook
Open the notebook file and execute all cells.
<!-- 📁 Project Structure -->
├── CNN(2).ipynb
├── README.md
<!-- 🎯 Output -->

The model predicts handwritten digits such as:

Input Image → Predicted Digit

Example:

Image of digit 5 → Prediction: 5
<!-- 📚 Learning Outcomes -->

Through this project, you will learn:

Basics of Deep Learning
Working with CNNs
Image Classification
Model Evaluation
Data Visualization