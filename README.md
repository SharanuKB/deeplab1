🧠 MNIST Handwritten Digit Classification using TensorFlow

A simple deep learning project that uses TensorFlow/Keras to classify handwritten digits from the MNIST dataset.

The project demonstrates the complete machine learning workflow: loading data, preprocessing images, building a neural network, training the model, evaluating performance, visualizing training results, and making predictions on test images.

📌 Project Overview

The MNIST dataset contains 70,000 grayscale images of handwritten digits from 0 to 9.

This project uses a fully connected neural network to learn patterns from the handwritten digits and predict the correct digit for previously unseen images.

Key Features

Loads the MNIST dataset using TensorFlow/Keras

Displays sample handwritten digits

Normalizes image pixel values

Builds a neural network using Keras

Trains the model for 10 epochs

Evaluates the model on test data

Visualizes training and validation accuracy

Visualizes training and validation loss

Makes predictions on test images

Compares actual and predicted labels

🛠️ Technologies Used

Python

TensorFlow

NumPy

Matplotlib

Keras

MNIST Dataset

🏗️ Model Architecture

The neural network consists of the following layers:

Input Image (28 × 28)
        ↓
Flatten
        ↓
Dense Layer (128 neurons)
        ↓
ReLU Activation
        ↓
Dense Layer (10 neurons)
        ↓
Softmax Activation
        ↓
Predicted Digit (0–9)

Model Configuration
Layer	Configuration
Input	28 × 28 grayscale image
Flatten	Converts image to 784 values
Dense	128 neurons
Activation	ReLU
Output Dense	10 neurons
Output Activation	Softmax
Optimizer	Adam
Loss Function	Sparse Categorical Crossentropy
Epochs	10
📂 Project Structure
MNIST-Digit-Classification/
│
├── mnist_classification.py
├── README.md
├── requirements.txt
└── screenshots/
    ├── sample_images.png
    ├── accuracy.png
    ├── loss.png
    └── predictions.png


The filenames can be changed according to your actual project files.

🚀 Installation
1. Clone the repository
git clone https://github.com/SharanuKB/deeplab1.git

2. Navigate to the project directory
cd YOUR-REPOSITORY

3. Install the required libraries
pip install tensorflow numpy matplotlib


Alternatively, if you have a requirements.txt file:

pip install -r requirements.txt

▶️ How to Run

Run the Python script:

python mnist_classification.py


The program will:

Download/load the MNIST dataset.

Display sample training images.

Normalize the image data.

Create the neural network.

Train the model.

Evaluate the model using the test dataset.

Display training and validation graphs.

Predict the digits in five test images.

📊 Results

After training, the model reports the test loss and test accuracy.

Example:

Test Loss: 0.08
Test Accuracy: 0.97


Actual results may vary slightly depending on the environment and training run.

📈 Training Visualization

The project generates two graphs:

Accuracy

The accuracy graph shows how the model's training and validation accuracy changes over the 10 epochs.

Loss

The loss graph shows how the training and validation loss changes during training.

🔍 Prediction Example

The final section of the program displays five test images with:

A: Actual Label
P: Predicted Label


For example:

A: 7
P: 7


This allows the model's predictions to be visually compared with the actual MNIST labels.

📚 What I Learned

Through this project, I learned:

How to load datasets using TensorFlow

Image preprocessing and normalization

How neural networks process image data

How to build models using Keras

Choosing an appropriate loss function and optimizer

Training and validating a neural network

Evaluating model performance

Visualizing training metrics

Using a trained model for predictions

🔮 Future Improvements

Possible improvements include:

Using a Convolutional Neural Network (CNN) for better image classification

Adding a confusion matrix

Testing different network architectures

Using dropout to reduce overfitting

Saving and loading the trained model

Creating a web interface for handwritten digit prediction

Allowing users to draw a digit and classify it in real time

📜 Dataset

This project uses the MNIST handwritten digit dataset, which is commonly used for experimenting with image classification and machine learning.

👨‍💻 Author

Your Name

GitHub: https://github.com/SharanuKB

⭐ If you found this project useful, consider giving the repository a star!
