# END TO END MACHINE LEANIING PROJECT

# Day 1->
The basic project setup, including GitHub integration, environment management, and package configuration, is now complete. In the next session, the focus will be on developing the formal project structure and implementing logging and exception handling.
# Key Points:
1. The setup.py file is essential for packaging the project, and requirements.txt lists all necessary dependencies.
2. Using .gitignore prevents unnecessary files, such as environment folders, from being committed to the repository.

# Day 2->
The project folder contains a notebook folder with the data file student.csv, and two files: one for EDA and one for model training. EDA should be performed in a Jupyter notebook, as it is the best environment for such analysis. Observations from EDA are crucial and should be communicated to stakeholders, with reasons provided for each step taken.

So machine learning project lifecycle 
1. Understanding the project statement very clearly
2. Data collection from kaggle
3. Data checks and EDA
4. Data preprocessing (cleaning + duplicate values + info about data)
5. Model training and selection
6. Model evaluation and deployment
The problem statement is to understand how student performance test scores are affected by variables such as gender, ethnicity, parental level of education, lunch, and test preparation course. The dataset consists of 1000 rows and 8 columns, providing a manageable starting point.

# EDA Steps and Observations
Begin by importing necessary libraries and selecting the Python kernel. The folder structure includes a notebook directory with data, EDA, and model training files. EDA involves checking for missing values, duplicate values, data types, unique values per column, and basic statistics. Observations and insights should be documented at each step.

Model Training Preparation
Proceed to model training by ensuring all required libraries are installed, such as scikit-learn, CatBoost, and XGBoost. Handle categorical features with one-hot encoding and numerical features with standard scaling. Use pipelines and column transformers to streamline preprocessing.

Train-Test Split and Evaluation Metrics
Split the data into training and testing sets. Define evaluation metrics such as mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), and R2 score to assess model performance.

Model Training and Selection
Train multiple regression models such as Linear Regression, Ridge, CatBoost, and XGBoost. Fit the models, make predictions, and evaluate them using the defined metrics. Select the best-performing model based on R2 score and other evaluation results.

Modular Coding and Project Organization
The next steps involve converting the Jupyter notebook code into modular Python scripts. Functions for evaluation, model training, and data splitting will be organized into utility files. This modular approach ensures code reusability and maintainability.

Version Control and Final Steps
Commit the code and data files to the GitHub repository using git commands. The repository link is provided in the description. The session covered the problem statement, EDA, and model training. Future tutorials will focus on modular coding.
