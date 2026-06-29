# Garbage Classification using Convolutional Neural Networks (CNN)

This project implements a Convolutional Neural Network (CNN) to classify garbage images into six categories: **cardboard, glass, metal, paper, plastic, and trash**. The model is built using TensorFlow/Keras and demonstrates the complete deep learning workflow, including data preprocessing, model training, evaluation, and prediction.

---

# Project Overview

Proper waste segregation is essential for effective recycling and environmental sustainability. Manual sorting of waste is time-consuming and prone to errors. This project uses a Convolutional Neural Network (CNN) to automatically classify waste images into different categories, providing a foundation for intelligent waste management systems.

---

# Features

* Image preprocessing and normalization
* Data loading using `ImageDataGenerator`
* Training and validation dataset split
* CNN model development using TensorFlow/Keras
* Model training and evaluation
* Accuracy and loss visualization
* Prediction on new test images
* Multi-class image classification

---

# Dataset

The dataset consists of six waste categories:

* Cardboard
* Glass
* Metal
* Paper
* Plastic
* Trash

The dataset contains approximately **2,500+ images** distributed across these classes.

---

# Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* OpenCV
* Jupyter Notebook

---

# Model Architecture

The CNN model includes:

* Input Layer (128 × 128 RGB Images)
* Convolutional Layers
* ReLU Activation
* Max Pooling Layers
* Dropout Layers
* Flatten Layer
* Fully Connected (Dense) Layers
* Softmax Output Layer

---

# Project Structure

```text
DL_Project_Garbage_Classification_CNN/
│
├── dataset/
│   ├── cardboard/
│   ├── glass/
│   ├── metal/
│   ├── paper/
│   ├── plastic/
│   └── trash/
│
├── Garbage_Classification_CNN.ipynb
├── model.h5
├── test_images/
├── README.md
└── requirements.txt
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/DL_Project_Garbage_Classification_CNN.git
```

Navigate to the project directory:

```bash
cd DL_Project_Garbage_Classification_CNN
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

# Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Garbage_Classification_CNN.ipynb
```

Run all cells to:

1. Load the dataset
2. Preprocess images
3. Train the CNN model
4. Evaluate model performance
5. Test the model on new images

---

# Workflow

1. Load image dataset
2. Normalize image pixel values
3. Create training and validation datasets
4. Build the CNN model
5. Train the model
6. Evaluate accuracy and loss
7. Save the trained model
8. Predict garbage categories for new images

---

# Sample Classes

| Class     | Description                    |
| --------- | ------------------------------ |
| Cardboard | Cardboard waste                |
| Glass     | Glass bottles and containers   |
| Metal     | Metal cans and scrap           |
| Paper     | Paper products                 |
| Plastic   | Plastic bottles and containers |
| Trash     | Mixed or non-recyclable waste  |

---

# Future Improvements

* Apply data augmentation techniques
* Use transfer learning models such as MobileNetV2, ResNet50, or EfficientNet
* Hyperparameter tuning
* Deploy the model using FastAPI or Flask
* Build a web application using Streamlit
* Deploy using Docker
* Optimize for real-time waste classification

---

# Results

The CNN model successfully learns to classify garbage images into six categories. Model performance can be further improved using transfer learning, larger datasets, and advanced data augmentation techniques.

---

# Author

**Haziqa Shakir Khan**

AI & Data Science Student

---

# License

This project is licensed under the MIT License and is intended for educational and research purposes.
