# 🌸 Iris Flower Classification Project

### Project Objective
The goal of this project is to build and evaluate a machine learning model capable of classifying the species of an iris flower (Setosa, Versicolor, or Virginica) based on its sepal and petal measurements. This project serves as a beginner-friendly introduction to the complete machine learning workflow.

---

### Dataset
This project uses the classic "Iris" dataset, sourced directly from the `scikit-learn` library. The dataset contains 150 samples, with 50 samples for each of the three iris species.

The features used for prediction are:
* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

---

### Methodology
1.  **Data Loading:** The Iris dataset was loaded from `scikit-learn`.
2.  **Exploratory Data Analysis (EDA):** I visualized the relationships between the features using a pairplot to understand the data's structure and separability.
3.  **Data Splitting:** The data was split into a training set (70%) and a testing set (30%) to ensure the model is evaluated on unseen data.
4.  **Model Training:** A **Decision Tree Classifier** was chosen for its simplicity and interpretability. The model was trained on the training data.
5.  **Evaluation:** The trained model was used to make predictions on the test set.

---

### Results
The final model achieved an accuracy of **93.33%** on the test data, demonstrating its effectiveness in classifying the iris species correctly.

---

### Tools and Libraries Used
* **Python**
* **Pandas:** For data manipulation and analysis.
* **Matplotlib & Seaborn:** For data visualization.
* **Scikit-learn:** For loading the dataset, splitting the data, and building the machine learning model.
* **Google Colab:** As the development environment.
