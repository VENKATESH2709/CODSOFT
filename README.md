Credit Card Fraud Detection using Logistic Regression

Description
This project involves building a machine learning model to detect fraudulent credit card transactions. The dataset used for this project contains a mix of legitimate and fraudulent transactions, and the goal is to accurately classify transactions as fraudulent or not. Logistic Regression is used as the primary model for classification.

Files
task_1_codsoft (1).ipynb: The Jupyter Notebook containing all the code for data loading, preprocessing, model training, and evaluation.
Installation
To run this project, you need to have the following installed:

Python 3.x
Jupyter Notebook
Required Python libraries (specified in requirements.txt)
You can install the necessary libraries using:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook task_1_codsoft (1).ipynb
Run the cells in the notebook to execute the code step by step.

Notebook Contents
Data Loading and Preprocessing
The dataset is loaded and preprocessed to handle missing values, categorical variables, and scaling of numerical features.
Exploratory Data Analysis (EDA)
Various plots and statistics are generated to understand the distribution of the data and identify any patterns.
Model Training
The Logistic Regression model is trained on the preprocessed dataset.
Model Evaluation
The performance of the model is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
Results
The evaluation results of the model are displayed and analyzed.
Confusion matrix and ROC curve are plotted to visualize the performance.
Conclusion
This project demonstrates the application of Logistic Regression for detecting fraudulent credit card transactions. The model's performance is assessed using various metrics to ensure its effectiveness in identifying fraud.
