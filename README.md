# Iris Flower Classification

## Task Objectives

The objective of this project is to classify iris flowers into three species (Setosa, Versicolor, and Virginica) based on their features (sepal length, sepal width, petal length, and petal width). The project involves the following steps:

1. **Importing Libraries**: Import necessary libraries for data manipulation, visualization, and model building.
2. **Loading Dataset**: Load the Iris dataset from a CSV file.
3. **Data Preprocessing**: Handle missing values, drop unnecessary columns, and standardize the features.
4. **Exploratory Data Analysis (EDA)**: Visualize the data using pair plots and heatmaps to understand the relationships between features.
5. **Model Selection**: Train and evaluate multiple machine learning models (KNN, Decision Tree, Random Forest, SVM) using cross-validation.
6. **Best Model Selection and Evaluation**: Select the best model based on accuracy and evaluate it using classification reports and confusion matrices.
7. **Feature Importance**: Determine the importance of each feature using the Random Forest model.

## Steps to Run the Project

1. **Clone the Repository**: Clone the repository to your local machine.
    ```sh
    git clone https://github.com/abhaystar2004/Iris_classification
    cd Iris_classification
    ```

2. **Install Dependencies**: Install the required Python libraries.
    ```sh
    pip install pandas seaborn matplotlib scikit-learn
    ```

3. **Run the Jupyter Notebook**: Open and run the Jupyter Notebook `Iris_flower_classification.ipynb`.
    ```sh
    jupyter notebook Iris_flower_classification.ipynb
    ```

4. **Follow the Notebook**: Execute the cells in the notebook sequentially to perform data preprocessing, model training, evaluation, and feature importance analysis.

## Additional Information

- **Dataset**: The Iris dataset used in this project is available in the file `iris.csv`.
- **Models Evaluated**: The project evaluates four machine learning models: K-Nearest Neighbors (KNN), Decision Tree, Random Forest, and Support Vector Machine (SVM).
- **Best Model**: The best model is selected based on cross-validation accuracy and further evaluated using classification reports and confusion matrices.
- **Feature Importance**: The importance of each feature is determined using the Random Forest model and visualized using a bar plot.

> Author: Abhay Sharma
