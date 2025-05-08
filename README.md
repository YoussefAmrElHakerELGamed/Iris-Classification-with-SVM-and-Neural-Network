
# Iris Classification with SVM and Neural Network

This project explores and compares two popular classification techniques—Support Vector Machine (SVM) and a Feedforward Neural Network—on the classic Iris dataset. It includes data preprocessing, model training, evaluation, and visualization to analyze performance differences.

## 📊 Overview

The Iris dataset contains 150 samples of iris flowers with 4 features each (sepal length, sepal width, petal length, petal width) and class labels (setosa, versicolor, virginica).

This project:

- Performs Exploratory Data Analysis (EDA)
- Applies standard preprocessing (train-test split, scaling)
- Trains both an SVM and a Neural Network classifier
- Evaluates models using accuracy, F1-score, confusion matrix, and ROC-AUC
- Visualizes results to compare performance

## 📁 Project Structure

```

├── assignment 3.ipynb           # Main Python script
└── README.md                    # Project description

````

## ⚙️ Setup & Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/iris-classification-comparison.git
cd iris-classification-comparison
````

2. (Optional) Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn sklearn tensorflow
```

## 🚀 Run the Code

```bash
python assignment 3.ipynb
```

This script will:

* Load and visualize the Iris dataset
* Train an SVM and a Neural Network
* Display evaluation metrics
* Show a loss curve for the neural network
* Save and display the ROC curve comparison plot

## 📈 Results Summary

* SVM achieved nearly perfect classification with AUCs ≈ 0.99–1.00
* Neural Network performed well overall but had slightly lower performance on Class 1 (AUC ≈ 0.81)
* ROC curves and confusion matrices offer insight into classification boundaries

## 📚 Learn More

* Iris dataset: [https://scikit-learn.org/stable/auto\_examples/datasets/plot\_iris\_dataset.html](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
* SVMs in scikit-learn: [https://scikit-learn.org/stable/modules/svm.html](https://scikit-learn.org/stable/modules/svm.html)
* Keras Sequential model guide: [https://keras.io/guides/sequential\_model/](https://keras.io/guides/sequential_model/)

## 📌 License

This project is licensed under the MIT License. Feel free to fork and modify for educational or research purposes.
