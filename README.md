# 🩺 Diabetes Prediction with Machine Learning

This project implements a machine learning model to predict the likelihood of diabetes based on diagnostic measurements. The model is built using a Support Vector Machine (SVM) and is trained on the PIMA Diabetes Dataset.

The entire workflow, from data analysis to model deployment, is encapsulated in a clean and reproducible Jupyter Notebook.

## 📊 Dataset

The dataset used is the PIMA Diabetes Dataset, which is publicly available. It contains medical predictor variables and one target variable, 'Outcome' (0 for non-diabetic, 1 for diabetic).

## ✨ Features

* **Exploratory Data Analysis (EDA):** The notebook includes visualizations to understand the data, such as distributions of key features (Glucose, BMI) and a correlation heatmap.
* **Robust Pipeline:** The model uses `scikit-learn`'s `Pipeline` to chain together a `StandardScaler` for feature standardization and a `Support Vector Classifier` with a linear kernel. This ensures the model is trained on properly scaled data.
* **Stratified Sampling:** The data is split into training and testing sets using stratified sampling to maintain the original proportion of outcomes, ensuring fair and accurate model evaluation.
* **Comprehensive Evaluation:** The model's performance is evaluated using key metrics and visualizations, including:
    * Accuracy Score
    * Confusion Matrix
    * ROC Curve and AUC Score
* **Interactive Prediction System:** The project features a simple, interactive system built with `ipywidgets` that allows a user to input medical data and receive a real-time diabetes prediction.

## 💻 How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone <repository-url>
    ```

2.  **Install Dependencies:**
    The project requires the following Python libraries. You can install them using `pip`:
    ```bash
    pip install numpy pandas scikit-learn matplotlib seaborn ipywidgets
    ```

3.  **Run the Notebook:**
    Open the `Diabetes_Prediction_Project.ipynb` file in a Jupyter environment (e.g., Jupyter Notebook, JupyterLab, or Google Colab) and run the cells in order.

## 📂 Project Structure

* `Diabetes_Prediction_Project.ipynb`: The main Jupyter Notebook containing all the code for data analysis, model training, evaluation, and the predictive system.
* `diabetes.csv`: The dataset used for this project.

## 🤝 Acknowledgements

This project was completed as part of an internship program with **InternPE**.
