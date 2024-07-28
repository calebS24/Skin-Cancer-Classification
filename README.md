# Capstone Project - CSE445 2024

Welcome to the Capstone Project repository for CSE445 2024. This project focuses on classifying skin lesions using deep learning techniques. We are utilizing the HAM10000 dataset and implementing various machine learning algorithms such as Convolutional Neural Networks (CNN), K-Nearest Neighbors (KNN), Random Forest, and Decision Tree.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Algorithms](#algorithms)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to develop an effective system for classifying skin lesions based on images. The project leverages deep learning and machine learning algorithms to achieve high accuracy in classification, aiding in the early detection and treatment of skin diseases.

## Dataset

We are using the HAM10000 ("Human Against Machine with 10000 training images") dataset. This dataset consists of 10,015 dermatoscopic images of pigmented lesions, which are used for training and evaluating our models.

- **Source**: [HAM10000 Dataset](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
- **Classes**: 7 different types of skin lesions
- **Format**: JPEG images with corresponding metadata

## Algorithms

The project implements the following algorithms:

1. **Convolutional Neural Networks (CNN)**:
   - Used for extracting features from images and performing classification.
2. **K-Nearest Neighbors (KNN)**:
   - A simple, instance-based learning algorithm for classification.
3. **Random Forest**:
   - An ensemble learning method for classification and regression.
4. **Decision Tree**:
   - A non-parametric supervised learning method used for classification.

## Installation

To run this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Capstone-CSE445-2024/Capstone.git
   cd Capstone
2. **Set up a virtual environment (optional but recommended):**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
3. **Install the required dependencies:**:
   ```bash
   pip install -r requirements.txt

## Usage

To train and evaluate the models, follow these steps:

1. **Preprocess the dataset**:
   ```bash
   python preprocess.py
2. **Train the models**:
   ```bash
   python train.py
3. **Evaluate the models**:
   ```bash
   python preprocess.py

## Project Structure

```kotlin
Capstone/
│
├── data/
│   ├── raw/
│   ├── processed/
│
├── models/
│   ├── cnn_model.py
│   ├── knn_model.py
│   ├── random_forest.py
│   ├── decision_tree.py
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── Model_Training.ipynb
│
├── scripts/
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
│
├── requirements.txt
├── README.md
└── .gitignore
```
## Contributing
We welcome contributions to improve this project. If you have any suggestions or improvements, please create a pull request or open an issue.

## License
This project is licensed under the MIT License - see the LICENSE file for details








