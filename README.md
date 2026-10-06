# MNIST Digit Classification

A machine learning project for recognizing handwritten digits using the **MNIST dataset** and a neural network built with **TensorFlow/Keras**.

## Project Overview

The goal of this project is to build and evaluate a machine learning model capable of classifying handwritten digits from 0 to 9.

The project covers the complete machine learning workflow, including data loading, preprocessing, model development, training, evaluation, and prediction.

## Dataset

The **MNIST dataset** contains 70,000 grayscale images of handwritten digits:

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* 10 classes representing digits 0–9

The dataset is loaded directly through TensorFlow/Keras.

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* TensorFlow / Keras

## Project Workflow

### 1. Data Loading

The MNIST dataset is loaded and separated into training and testing sets.

### 2. Data Exploration

The images and their corresponding labels are explored to understand the structure of the dataset.

### 3. Data Preprocessing

The image data is normalized and prepared for input into the neural network.

### 4. Model Building

A neural network model is created using TensorFlow/Keras.

### 5. Model Training

The model is trained using the training dataset and evaluated using validation data.

### 6. Model Evaluation

The trained model is evaluated on the test dataset using metrics such as accuracy.

### 7. Predictions

The trained model is used to predict handwritten digits from previously unseen images.

## Results

**Test Accuracy:** Add your final accuracy here.

For example:

```text
Test Accuracy: 98.00%
```

The project also includes visualizations such as training/validation performance and a confusion matrix.

## Project Structure

```text
mnist-digit-classification/
│
├── MNIST_Classification.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images/
    ├── confusion_matrix.png
    └── sample_predictions.png
```

## How to Run

Clone or download this repository and open the notebook:

```text
MNIST_Classification.ipynb
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

Then run the notebook using Jupyter Notebook or JupyterLab.

## Key Learning Outcomes

This project helped develop practical experience with:

* Data preprocessing
* Exploratory data analysis
* Image classification
* Neural networks
* TensorFlow/Keras
* Model training and validation
* Model evaluation
* Confusion matrices
* Making predictions with a trained model

## Future Improvements

Possible improvements include:

* Experimenting with different neural network architectures
* Implementing a Convolutional Neural Network (CNN)
* Hyperparameter tuning
* Comparing multiple models
* Improving classification accuracy
* Deploying the trained model as a web application

## Author

**Mohammad Saljoq**

Machine Learning & Data Analytics Student
