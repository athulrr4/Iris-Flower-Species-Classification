# 🌸 Iris Flower Species Classification

## 📌 Project Overview

This project demonstrates the classification of Iris flower species using a **Decision Tree Classifier**, a supervised machine learning algorithm.

The model predicts the species of an Iris flower based on four measurements:
- Sepal length
- Sepal width
- Petal length
- Petal width

The three species classified are Setosa, Versicolor, and Virginica.

This notebook was provided as part of a learning assignment/coursework.

## 🎯 Project Objectives

- Load and explore the Iris dataset.
- Understand the relationship between flower measurements and species.
- Visualize the dataset using Matplotlib.
- Split the dataset into training and testing sets.
- Train a Decision Tree classification model.
- Evaluate model accuracy.
- Understand how tree depth affects model performance.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Project Structure

```text
Iris-Flower-Species-Classification/
│
├── 01_leaf_species_detection.ipynb
└── README.md
```

## 📊 Dataset

The notebook uses the classic Iris dataset, which contains:

- 150 flower samples
- 4 numerical features
- 3 species categories

**Target species:**
- Setosa
- Versicolor
- Virginica

The notebook expects the dataset at `data/iris.csv`.

## 🤖 Machine Learning Algorithm

**Decision Tree Classifier**

A Decision Tree is a supervised machine learning algorithm that makes predictions by learning decision rules from the training data.

The notebook also compares different `max_depth` values to understand their effect on test accuracy.

## ⚙️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/athulrr4/Iris-Flower-Species-Classification.git
   ```

2. Open the project folder:

   ```bash
   cd Iris-Flower-Species-Classification
   ```

3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `01_leaf_species_detection.ipynb` and run the cells.

**Note:** The notebook expects `data/iris.csv`. Make sure this dataset file is available before running the notebook.

## 📚 Learning Outcomes

- Understanding classification problems.
- Exploring and visualizing datasets.
- Training and testing a Decision Tree model.
- Evaluating model accuracy.
- Understanding the effect of tree depth on performance.

## 👨‍💻 Author

**ATHUL R.R**

GitHub: [@athulrr4](https://github.com/athulrr4)

## 🙏 Acknowledgement

This notebook was provided by our instructor as part of the learning coursework and is shared for educational purposes.

