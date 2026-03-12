# 🧠 Deep Learning Labs

A collection of deep learning experiments covering neural networks, CNNs, ResNets, and autoencoders — implemented from scratch and with pretrained models.

---

## 📋 Table of Contents

- [Lab 01 — Feedforward Neural Network & Backpropagation](#lab-01--feedforward-neural-network--backpropagation)
- [Lab 02 — ANN for MNIST Classification](#lab-02--ann-for-mnist-classification)
- [Lab 03 — CNN for MNIST Classification](#lab-03--cnn-for-mnist-classification)
- [Lab 04 — ResNet for Skin Lesion & Deepfake Classification](#lab-04--resnet-for-deepfake-classification)
- [Lab 05 — AutoEncoders for MNIST Compression](#lab-05--autoencoders-for-mnist-compression)

---

## Lab 01 — Feedforward Neural Network & Backpropagation

Implemented a simple neural network **from scratch** in Python without any deep learning libraries.

- **Dataset:** Iris
- **Techniques:** Forward propagation, MSE loss, gradient descent, backpropagation
- Manual weight updates via computed gradients

---

## Lab 02 — ANN for MNIST Classification

Built a fully connected neural network to classify handwritten digits.

- **Dataset:** MNIST
- **Evaluation:** Test accuracy
- Baseline model for comparison with convolutional architectures

---

## Lab 03 — CNN for MNIST Classification

Implemented a Convolutional Neural Network for improved digit classification.

- **Dataset:** MNIST
- **Comparison:** ANN vs CNN on accuracy and number of parameters
- Demonstrates the efficiency of shared-weight convolutional layers

---

## Lab 04 — ResNet for Skin Lesion & Deepfake Classification

Applied ResNet architectures to two real-world classification tasks.

- **Models:** ResNet-34 (from scratch), ResNet-152 (pretrained)
- **Tasks:** Skin lesion classification, deepfake detection
- **Evaluation:** Accuracy, precision, recall, F1-score, AUC

---

## Lab 05 — AutoEncoders for MNIST Compression

Explored dimensionality reduction using PCA and autoencoders.

- **Dataset:** MNIST
- **Latent Space:** 4-dimensional representation
- **Visualization:** t-SNE plots of latent space
- **Comparison:** PCA reconstruction vs autoencoder reconstruction

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)

---

## 🚀 Getting Started
```bash
# Clone the repository
git clone https://github.com/your-username/deep-learning-labs.git
cd deep-learning-labs

# Install dependencies
pip install -r requirements.txt

# Navigate to a lab
cd lab01
python main.py
```

---

## 📄 License

This project is for educational purposes. Feel free to explore and build upon it.