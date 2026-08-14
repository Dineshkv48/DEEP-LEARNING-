# AI23531 - Deep Learning Lab

This repository contains the implementations and experiments performed as part of the **AI23531 Deep Learning Laboratory**.

The lab covers fundamental and advanced concepts in Deep Learning, including Neural Networks, Multi-Layer Perceptrons, optimization techniques, Convolutional Neural Networks, Recurrent Neural Networks, image captioning, Variational Autoencoders, LSTM-based text generation, and Generative Adversarial Networks.

## 🧠 Topics Covered

- Three-Layer Neural Network
- Multi-Layer Perceptron (MLP)
- Backpropagation
- Stochastic Gradient Descent (SGD)
- SGD with Momentum
- Adam Optimizer
- Convolutional Neural Networks (CNN)
- VGG
- ResNet
- GoogLeNet
- Bidirectional RNN
- Feedforward Neural Networks
- Image Captioning
- Variational Autoencoder (VAE)
- LSTM Text Generation
- Generative Adversarial Networks (GAN)

## 🧪 Lab Experiments

| No. | Experiment | Dataset |
|-----|-------------|---------|
| 1 | Three-Layer Neural Network From Scratch | MNIST |
| 2 | Multi-Layer Perceptron (MLP) for Classification | Iris |
| 3 | SGD with Momentum vs Adam Optimizer | CIFAR-10 |
| 4 | Implementation of a Convolutional Neural Network (CNN) | CIFAR-10 |
| 5 | Comparative Analysis of VGG, ResNet, and GoogLeNet | Dogs vs Cats |
| 6 | Bidirectional RNN vs Feedforward NN for Time-Series Prediction | Airline Passenger |
| 7 | Image Captioning using CNN-RNN Architecture | MS COCO |
| 8 | Image Generation using Variational Autoencoder (VAE) | CelebA |
| 9 | Text Generation using LSTM Networks | Shakespeare Corpus |
| 10 | Image Generation using Generative Adversarial Network (GAN) | LSUN |

The experiments and suggested datasets are based on the AI23531 Deep Learning Lab Manual. :contentReference[oaicite:1]{index=1}

## 🛠️ Technologies Used

- **Python 3.x**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**
- **TensorFlow / Keras**
- **PyTorch**
- **Hugging Face Transformers**
- **PIL (Python Imaging Library)**

## 📚 Experiment Details

### 1. Three-Layer Neural Network From Scratch

Implement a three-layer neural network using Python from scratch and train it using the backpropagation algorithm for handwritten digit recognition.

**Dataset:** MNIST

### 2. Multi-Layer Perceptron (MLP)

Develop an MLP for classification and experiment with different hidden layers and activation functions.

**Dataset:** Iris

### 3. SGD with Momentum vs Adam

Implement and compare SGD with Momentum and the Adam optimizer based on convergence and model performance.

**Dataset:** CIFAR-10

### 4. Convolutional Neural Network

Implement a CNN for image classification and visualize the learned filters.

**Dataset:** CIFAR-10

### 5. VGG vs ResNet vs GoogLeNet

Compare three popular CNN architectures and analyze their classification performance.

**Models:**
- VGG
- ResNet
- GoogLeNet

**Dataset:** Dogs vs Cats

### 6. Bidirectional RNN vs Feedforward Neural Network

Use a Bidirectional RNN for time-series prediction and compare its performance with a traditional Feedforward Neural Network.

**Dataset:** Airline Passenger Dataset

### 7. Image Captioning

Combine image feature extraction and sequence generation to generate meaningful captions for images.

**Dataset:** MS COCO

### 8. Variational Autoencoder

Implement a VAE to learn latent representations and generate new images from the learned distribution.

**Dataset:** CelebA

### 9. Text Generation using LSTM

Build an LSTM-based text generation model capable of generating sequences from a text corpus.

**Dataset:** Shakespeare Corpus

### 10. Generative Adversarial Network

Train a GAN to generate new images and evaluate the quality of generated samples.

**Dataset:** LSUN

The experiment objectives and scope are based on the laboratory manual. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## 🚀 Mini Project

The laboratory also includes a Deep Learning mini project.

The project involves:

1. Selecting a Deep Learning problem.
2. Researching related work.
3. Selecting a suitable dataset.
4. Preprocessing the dataset.
5. Developing baseline models.
6. Experimenting with advanced architectures.
7. Training and evaluating the models.
8. Comparing results using suitable evaluation metrics.
9. Documenting the findings.
10. Presenting the results and future improvements.

Possible areas include:

- Image Classification
- Text Generation
- Anomaly Detection
- Computer Vision
- Natural Language Processing
- Generative AI

The lab manual recommends using frameworks such as TensorFlow or PyTorch and evaluating models with metrics such as accuracy and F1-score. :contentReference[oaicite:4]{index=4}

## 🎯 Course Outcomes

After completing this laboratory, the following concepts are covered:

- Implementing the architecture of a neural network.
- Applying different training and optimization techniques.
- Designing and evaluating CNN models for image classification.
- Understanding RNNs and their applications.
- Applying autoencoders to different problems.
- Understanding and implementing deep generative models.

These outcomes are specified in the AI23531 Deep Learning Lab Manual. :contentReference[oaicite:5]{index=5}

## 📁 Repository Structure

```text
DEEP-LEARNING/
│
├── EX01_Three_Layer_Neural_Network/
├── EX02_MLP_Classification/
├── EX03_SGD_Momentum_vs_Adam/
├── EX04_CNN/
├── EX05_VGG_ResNet_GoogLeNet/
├── EX06_Bidirectional_RNN/
├── EX07_Image_Captioning/
├── EX08_VAE_Image_Generation/
├── EX09_LSTM_Text_Generation/
├── EX10_GAN_Image_Generation/
│
├── Mini_Project/
│
└── README.md
