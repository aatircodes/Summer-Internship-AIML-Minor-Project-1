# Breast Cancer Prediction Using Supervised Machine Learning

**Minor Project Report**

**Submitted By:** Mohd Aatir
**Course:** Master of Computer Applications (MCA)

---

## 📑 Table of Contents

* [Title](#title)
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Methodology](#methodology)
* [Results](#results)
* [Conclusion](#conclusion)
* [How to Run the Project](#how-to-run-the-project)
* [References](#references)

---

## Title

**Breast Cancer Prediction Using Supervised Machine Learning**

---

## Problem Statement

Breast cancer is one of the most common types of cancer affecting people worldwide. Early and accurate diagnosis plays a vital role in improving treatment outcomes and reducing mortality. However, analyzing numerous medical measurements manually can be time-consuming and may increase the possibility of diagnostic errors.

The objective of this project is to develop a supervised machine learning model capable of predicting whether a breast tumor is **Benign (non-cancerous)** or **Malignant (cancerous)** using diagnostic features obtained from medical examinations. Multiple supervised learning algorithms are implemented and compared to identify the model with the best predictive performance.

---

## Objectives

The primary objectives of this project are:

* Study the Breast Cancer Wisconsin Diagnostic Dataset.
* Preprocess and prepare the dataset for machine learning.
* Perform Exploratory Data Analysis (EDA).
* Train multiple supervised machine learning models.
* Evaluate each model using standard performance metrics.
* Compare the performance of all models and identify the best-performing algorithm.

---

## Dataset

The project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**, downloaded from Kaggle.

**Dataset Source:**
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

### Dataset Information

| Attribute       | Value                     |
| --------------- | ------------------------- |
| Total Records   | **569**                   |
| Features        | **30**                    |
| Target Variable | **Diagnosis**             |
| Classes         | Benign (B), Malignant (M) |

---

## Technologies Used

The following technologies and libraries were used during the development of this project:

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Joblib

---

## Methodology

The project follows the workflow below:

1. Import the required libraries.
2. Load the Breast Cancer Wisconsin Diagnostic Dataset.
3. Explore the dataset structure and statistical information.
4. Remove unnecessary columns.
5. Check for missing values and duplicate records.
6. Encode the target variable.
7. Perform Exploratory Data Analysis (EDA).
8. Select the feature and target variables.
9. Split the dataset into training and testing sets.
10. Apply feature scaling using **StandardScaler**.
11. Train the following supervised learning models:

    * Logistic Regression
    * Decision Tree
    * Random Forest
    * Support Vector Machine (SVM)
12. Evaluate each model using:

    * Accuracy Score
    * Classification Report
    * Confusion Matrix
13. Compare the performance of all models.

---

## Results

| Model                            |   Accuracy |
| -------------------------------- | ---------: |
| **Support Vector Machine (SVM)** | **98.25%** |
| Logistic Regression              | **97.37%** |
| Random Forest                    | **96.49%** |
| Decision Tree                    | **94.74%** |

The **Support Vector Machine (SVM)** achieved the highest accuracy (**98.25%**) and demonstrated the best overall classification performance on the testing dataset.

---

## Conclusion

This project successfully demonstrates the application of supervised machine learning techniques for breast cancer prediction. Four classification algorithms were implemented and evaluated using the Breast Cancer Wisconsin Diagnostic Dataset.

Among the tested models, the **Support Vector Machine (SVM)** achieved the highest accuracy of **98.25%**, making it the best-performing model for this dataset.

The results indicate that machine learning can effectively assist healthcare professionals in classifying breast tumors, supporting early diagnosis, and improving decision-making.

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

### 2. Navigate to the project directory

```bash
cd your-repository
```

### 3. Install the required dependencies

```bash
pip install numpy pandas matplotlib scikit-learn joblib notebook
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Open the notebook inside the `notebook` folder and run all cells sequentially to reproduce the complete workflow.

---

## References

1. Breast Cancer Wisconsin (Diagnostic) Dataset (Kaggle)
   https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

2. Scikit-learn Documentation
   https://scikit-learn.org/

3. Pandas Documentation
   https://pandas.pydata.org/

4. NumPy Documentation
   https://numpy.org/

5. Matplotlib Documentation
   https://matplotlib.org/

---

## Author

**Mohd Aatir**
**Master of Computer Applications (MCA)**
