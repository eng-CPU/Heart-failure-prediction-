# Heart Failure Prediction
ModelBuildingProject:
This repository contains a dataset and code for predicting heart failure using various machine learning models. The dataset includes clinical features that are crucial for early detection and management of heart failure.

## Dataset

The dataset consists of 918 instances with 12 features related to cardiovascular health. Each instance includes information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol Levels
- Fasting Blood Sugar
- Resting Electrocardiogram Results
- Maximum Heart Rate Achieved
- Presence of Exercise-Induced Angina
- ST Depression Measured During Exercise
- Slope of the Peak Exercise ST Segment
- Target Variable (HeartDisease: 1 indicates presence, 0 indicates absence)

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, tensorflow, keras

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/eng-CPU/Heart-failure-prediction-/edit/main/README.md
    ```
2. Navigate to the project directory:
    ```bash
    cd heart-failure-prediction
    ```
3. Install the required libraries.
   

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `Heart_Failure_Prediction.ipynb` notebook.
3. Apply the steps in the notebook to load the dataset, perform exploratory data analysis, and train machine learning models.

## Models

The following machine learning models are implemented in the notebook:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors
- Neural Network (using TensorFlow and Keras)

## Results

The performance of each model is evaluated using accuracy, precision, recall, and F1-score. The best performing model is highlighted in the results section of the notebook.


## Acknowledgements

- The dataset is sourced from [https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction]
---

Feel free to customize this README to better fit your project! If you have any specific requirements or additional sections you'd like to include, let me know!

