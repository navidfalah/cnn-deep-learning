# Deep Learning with CNNs on CIFAR-100 🖼️🤖

This project demonstrates **deep learning** using **Convolutional Neural Networks (CNNs)** on the **CIFAR-100 dataset**. The goal is to classify images into 100 categories using various CNN architectures such as **AlexNet**, **VGG16**, **ResNet50**, and **GoogleNet**. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **PyTorch** to build and train CNN models for image classification. 🤖📸
- Leverages the **CIFAR-100 dataset** for training and validation. 🧠🔍
- Implements various CNN architectures and evaluates their performance. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch torchvision matplotlib
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the CIFAR-100 dataset.
2. **Preprocess Data**: Applies data augmentation and normalization.
3. **Build Models**: Defines and trains CNN models using different architectures.
4. **Evaluate Models**: Evaluates the models' performance on the test set.
5. **Save Models**: Saves the trained models for future use.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the CIFAR-100 dataset.
  - Applies data augmentation and normalization.

- **Model Definition**:
  - Defines CNN architectures such as AlexNet, VGG16, ResNet50, and GoogleNet.
  - Uses cross-entropy loss for training.

- **Training**:
  - Trains the models using the training set.
  - Tracks training loss over epochs.

- **Evaluation**:
  - Evaluates the models' performance on the test set.
  - Prints the test accuracy for each model.

- **Model Saving**:
  - Saves the trained models for future use.

---

## Results 📊

- **Training Loss**: The models achieve low training loss over epochs.
- **Test Accuracy**: Evaluates the models' performance on the test set.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/10: Loss: 1.123
Epoch 2/10: Loss: 0.987
...
Accuracy of the network on the test images: 85.0%
```

---

## Dependencies 📦

- `torch`
- `torchvision`
- `matplotlib`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
