# Iris Flower Classification

## Overview

This repository contains a simple machine learning project aimed at classifying Iris flower species using the famous **Iris dataset**. The dataset includes 150 samples of Iris flowers with 4 features: sepal length, sepal width, petal length, and petal width. The goal is to classify these samples into one of three species: **Iris-setosa**, **Iris-versicolor**, or **Iris-virginica**.

## Requirements

To run the project, install the required Python libraries using the following command:
```bash
pip install -r requirements.txt
```

## Libraries Used

- **Pandas**: For data manipulation.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For building and evaluating machine learning models.

## Project Structure

- **iris_classification.ipynb**: Jupyter Notebook containing code for loading the dataset, data exploration, model building, training, and evaluation.
- **iris.csv**: Dataset file.
- **requirements.txt**: List of required Python libraries.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd iris-flower-classification
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook to explore the code and run the classification:
   ```bash
   jupyter notebook iris_classification.ipynb
   ```

## Results

The notebook implements and evaluates multiple machine learning models like **Logistic Regression**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machine (SVM)**. Model accuracy is compared, and visualizations help understand the dataset.
