❤️ Heart Disease Prediction Using Supervised Learning
📌 Project Overview

This project is a machine learning case study that explores the application of supervised learning techniques to heart disease classification.

The main objective is to analyze patient health data and compare different machine learning algorithms to predict whether heart disease is present. The project uses Python and popular data science libraries to perform data exploration, preprocessing, model training, and evaluation.

The notebook also explores regression algorithms to understand their performance on the dataset.

🎯 Objectives
Analyze and understand the heart disease dataset.
Perform exploratory data analysis (EDA) to identify patterns and relationships in the data.
Prepare the dataset for machine learning.
Apply and compare multiple supervised learning algorithms.
Evaluate model performance using appropriate metrics.
Identify the best-performing classification model based on experimental results.
📊 Dataset

The project uses a heart disease dataset containing 1,025 records and 14 columns, including 13 input features and one target variable.

The dataset includes the following attributes:

Feature	Description
age	Age of the patient
sex	Sex of the patient, encoded numerically
cp	Chest pain type
trestbps	Resting blood pressure
chol	Serum cholesterol level
fbs	Fasting blood sugar indicator
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina indicator
oldpeak	ST depression induced by exercise relative to rest
slope	Slope of the peak exercise ST segment
ca	Number of major vessels
thal	Thalassemia-related categorical value
target	Heart disease classification label

The target variable is used to distinguish between the two classes:

0 — Heart disease absent
1 — Heart disease present
🔍 Project Workflow
1. Data Loading and Exploration
Import the dataset using Pandas.
Examine the dataset structure, dimensions, and data types.
Generate descriptive statistics.
Explore feature distributions and relationships.
2. Exploratory Data Analysis (EDA)

EDA is performed to understand the characteristics of the data and investigate relationships between patient attributes and the target variable.

3. Feature Analysis and Preprocessing
Explore the relationship between input features and the target.
Use mutual information for feature analysis.
Apply feature scaling using StandardScaler.
Split the data into training and testing sets.
4. Model Training

The notebook implements the following classification algorithms:

Logistic Regression: A classification algorithm used to estimate the probability of a binary outcome.
K-Nearest Neighbors (KNN): Classifies observations based on nearby training examples.
Random Forest Classifier: Combines multiple decision trees to produce a classification.

The notebook also experiments with Linear Regression, Support Vector Regression (SVR), and Random Forest Regression.

5. Model Evaluation

The classification models are evaluated using:

Accuracy: Proportion of correct predictions.
Precision: Proportion of positive predictions that are correct.
Recall: Proportion of actual positive cases correctly identified.
F1-score: Harmonic mean of precision and recall.

The regression experiments use Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.

6. Model Comparison

The classification results are compared to determine which algorithm performs best on the test data.

📈 Results

The notebook's saved classification results are summarized below.

Model	Accuracy	Precision	Recall	F1-score
Logistic Regression	85.25%	87.50%	84.85%	86.15%
K-Nearest Neighbors	77.05%	77.14%	81.82%	79.41%
Random Forest Classifier	80.33%	81.82%	81.82%	81.82%
🏆 Best-Performing Model: Logistic Regression

Based on the recorded test results, Logistic Regression achieved the highest accuracy, precision, and F1-score among the three classification models.

These results indicate that Logistic Regression performed best in this particular experiment. Actual performance may vary with different data splits, preprocessing methods, and model settings.

🛠️ Technologies Used
Python — Programming language
Jupyter Notebook / Google Colab — Interactive development environment
NumPy — Numerical computation
Pandas — Data manipulation and analysis
Matplotlib — Data visualization
Seaborn — Statistical visualization
Scikit-learn — Preprocessing, machine learning algorithms, and evaluation metrics
🚀 Getting Started
Option 1: Run Using Google Colab
Open the Heart Disease notebook.
Download the notebook or open it in Google Colab.
Make sure the dataset file heart_disease (1).csv is available in the expected location, or update the file path to match where you upload it.
Run the notebook cells in order.
Review the visualizations, model evaluations, and comparison results.
Option 2: Run Locally

Prerequisites

Python 3.9 or a compatible Python version
Jupyter Notebook or JupyterLab
Git

Step 1: Clone the repository

git clone https://github.com/Rini892/Case-Study-on-Supervised-Learning-Heart_Disease.ipynb.git
cd Case-Study-on-Supervised-Learning-Heart_Disease.ipynb


Step 2: Install the required libraries

pip install numpy pandas matplotlib seaborn scikit-learn jupyter


Step 3: Start Jupyter Notebook

jupyter notebook


Step 4: Open and run the notebook

Open Heart_Disease.ipynb and execute the cells sequentially.

Note: The notebook currently references a CSV file named heart_disease (1).csv using a Google Colab-specific file path. Make sure the dataset is available and update the path when running locally. The CSV file is not listed among the repository's current files.

📁 Project Structure
Case-Study-on-Supervised-Learning-Heart_Disease.ipynb/
│
├── Heart_Disease.ipynb    # Data analysis and machine learning experiments
└── README.md              # Project documentation


The dataset should also be included in the repository or downloaded separately for reproducibility.

💡 Key Learnings
Understanding the supervised learning workflow.
Performing exploratory data analysis on structured health data.
Preparing numerical and categorical features for modeling.
Applying classification and regression algorithms.
Evaluating machine learning models with multiple performance metrics.
Comparing algorithms and interpreting experimental results.
⚠️ Disclaimer

This project is intended for educational and research purposes only. The model is an experimental machine learning exercise and is not intended for medical diagnosis, clinical decision-making, or treatment recommendations. Its predictions should not replace advice from qualified healthcare professionals.

👩‍💻 Author

Rini892

⭐ Acknowledgements

Thanks to the contributors and maintainers of the open-source Python data science and machine learning libraries used in this project.
