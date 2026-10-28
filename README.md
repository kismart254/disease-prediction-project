# \# Diabetes Prediction Using Random Forest Classifier

# 

# \##  Project Overview

# 

# This project focuses on predicting diabetes status using a \*\*Random Forest Classification algorithm\*\* in Python. It applies machine learning techniques to patient data to classify individuals into two categories: healthy or diabetic.

# 

# The project begins with Exploratory Data Analysis (EDA) to understand the dataset, identify missing values and duplicate records, examine outliers, and visualize relationships between variables. A Random Forest Classifier is then trained and evaluated before being saved for future predictions on new patient data.

# 

# \##  Objectives

# 

# \- Perform Exploratory Data Analysis on a diabetes dataset.

# \- Examine data distributions, potential outliers, and relationships between features.

# \- Develop a Random Forest Classification model for diabetes prediction.

# \- Evaluate model performance using accuracy and a confusion matrix.

# \- Save and load the trained model to predict diabetes status for new patient records.

# 

# \## Technologies and Libraries

# 

# The project uses the following tools and Python libraries:

# 

# \- \*\*Python\*\* — programming language.

# \- \*\*Pandas\*\* — data manipulation and analysis.

# \- \*\*NumPy\*\* — numerical computing.

# \- \*\*Matplotlib\*\* — data visualization.

# \- \*\*Seaborn\*\* — statistical data visualization.

# \- \*\*Scikit-learn\*\* — model training, data splitting, and evaluation.

# \- \*\*Joblib\*\* — saving and loading the trained model.

# \- \*\*Jupyter Notebook\*\* — interactive development environment.

# 

# \## 📂 Dataset Description

# 

# The project uses a dataset named `balanced\_diabetes\_500\_patients.csv`.

# 

# \*\*Note:\*\* The dataset must be available in the working directory when running the notebook. Its source and clinical validity should be verified before drawing real-world conclusions.

# 

# \## ⚙️ Project Workflow

# 

# \### 1. Data Loading and Exploration

# 

# The dataset is loaded using Pandas. Initial analysis includes:

# 

# \- Viewing sample records.

# \- Generating descriptive statistics.

# \- Checking dataset information and data types.

# \- Identifying missing values and duplicate records.

# 

# \### 2. Exploratory Data Analysis (EDA)

# 

# Matplotlib and Seaborn are used to visualize and explore the dataset.

# 

# The analysis includes:

# 

# \- Distribution of diabetes status.

# \- Box plots for selected numerical and risk-related features.

# \- Pair plots to explore relationships between features and diabetes status.

# \- Histograms to examine feature distributions.

# 

# \### 3. Data Preparation

# 

# The input features and target variable are separated. The `Patient\_ID` and `Diabetes\_Status` columns are excluded from the input features.

# 

# The dataset is then divided into training and testing sets using an 80:20 split, with `random\_state=42` to make the split reproducible.

# 

# \### 4. Model Development and Training

# 

# A Random Forest Classifier is created using the following configuration:

# 

# \- Number of estimators: 100 trees

# \- Maximum depth: 2

# \- Random state: 42

# 

# The model learns patterns from the training data and generates predictions for the test data.

# 

# \### 5. Model Evaluation

# 

# The model's performance is evaluated using:

# 

# \- \*\*Accuracy score:\*\* Measures the proportion of correct predictions.

# \- \*\*Confusion matrix:\*\* Summarizes correct and incorrect classifications across the target classes.

# 

# The actual evaluation results are printed when the notebook is executed.

# 

# \### 6. Model Saving and Prediction

# 

# The trained model is saved using Joblib and subsequently loaded for reuse.

# 

# New patient records are prepared in a Pandas DataFrame, and the loaded model predicts their diabetes status. The predicted numerical classes are mapped to readable labels:

# 

# \- `0` → Healthy

# \- `1` → Diabetic

# 

# These labels depend on the dataset's actual target encoding.

# 

# \##  How to Run the Project

# 

# \### Prerequisites

# 

# Install Python and the required libraries.

# 

# ```bash

# pip install numpy pandas matplotlib seaborn scikit-learn joblib jupyter

# ```

# 

# \### Step 1: Clone the Repository

# 

# ```bash

# git clone https://github.com/kismart254/disease-prediction-project>

# ```

# 

# Navigate into the cloned project directory:

# 

# ```bash

# cd <your-repository-folder>

# ```

# 

# Replace the placeholders with your actual GitHub repository URL and folder name.

# 

# \### Step 2: Add the Dataset

# 

# Place `balanced\_diabetes\_500\_patients.csv` in the directory from which the notebook will be executed.

# 

# \### Step 3: Open the Notebook

# 

# ```bash

# jupyter notebook

# ```

# 

# Open `real world diabetes dataset.ipynb` and execute the cells in order.

# 

# \### Step 4: Train and Evaluate the Model

# 

# Run the data preparation and model training cells to train the Random Forest Classifier, view the accuracy and confusion matrix, and save the model.

# 

# \### Step 5: Make Predictions

# 

# Execute the final cells to load the saved model and predict diabetes status for the example patient records.

# 

# \##  Results

# 

# The notebook calculates the model's accuracy and confusion matrix after testing.

# 

# Add your actual results here after running the notebook:

# 

# \- \*\*Accuracy:\*\*\[1.0]

# 

# 

# These results should be reported from the executed notebook rather than estimated.

# 

# \##  Key Learning Outcomes

# 

# Through this project, I gained practical experience in:

# 

# \- Conducting Exploratory Data Analysis.

# \- Cleaning and examining structured datasets.

# \- Visualizing data distributions and feature relationships.

# \- Training a supervised machine learning classification model.

# \- Evaluating a model using accuracy and a confusion matrix.

# \- Saving and reusing a trained model with Joblib.

# \- Applying a machine learning model to new input data.

# 

# \## Limitations and Disclaimer

# 

# This project is intended for educational and machine learning practice. Its predictions are not a medical diagnosis and should not be used to make clinical decisions.

# 

# The model's reliability depends on the dataset's quality, representativeness, and target-label definitions. Further evaluation using appropriate validation methods and independent data would be necessary before considering any real-world application.

# 

# \## 👨‍💻 Author

# 

# \*\*Victor Muchai\*\*

# 

# Aspiring Machine Learning Practitioner with an interest in applying data analysis and machine learning to practical problems.

# 



