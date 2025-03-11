# Iris Flower Classification

This project demonstrates how to classify Iris flowers into three species (`Setosa`, `Versicolor`, and `Virginica`) based on their sepal and petal measurements using a **Random Forest Classifier**. The code is implemented in Python using Google Colab and is designed to be simple and easy to understand.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [How to Run the Code](#how-to-run-the-code)
5. [Results](#results)
6. [License](#license)

---

## **Project Overview**

The goal of this project is to build a machine learning model that can classify Iris flowers into one of three species based on the following features:
- **Sepal Length** (in cm)
- **Sepal Width** (in cm)
- **Petal Length** (in cm)
- **Petal Width** (in cm)

The model uses a **Random Forest Classifier** from the `scikit-learn` library. The project includes:
- Data visualization using `seaborn` and `matplotlib`.
- Model training and evaluation.
- Feature importance analysis.
- A demonstration of making predictions on new data.

---

## **Dataset**

The dataset used in this project is the **Iris dataset**, which is a classic dataset in machine learning. It contains 150 samples of Iris flowers, with 50 samples from each of the following species:
- **Setosa**
- **Versicolor**
- **Virginica**

Each sample has four features:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width

The dataset is available in the `iris_data.csv` file.

---

## **Dependencies**

To run this project, you need the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the dependencies using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
