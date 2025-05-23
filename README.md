This repository provides a practical demonstration of building, saving, and loading a machine learning model using Python. It serves as a tutorial for understanding the workflow of model persistence, which is essential for deploying machine learning models in real-world applications.

Repository Contents
Creating_And_Saving_Model.ipynb: Jupyter notebook that walks through the process of training a machine learning model and saving it to disk.

Loading_And_Using_The_Model.ipynb: Jupyter notebook that demonstrates how to load the previously saved model and use it for making predictions.

train.csv: Dataset used for training the machine learning model.

Loan_Model/: Directory where the trained model is saved.

Prerequisites
Python 3.x

Jupyter Notebook

Required Python libraries:

pandas

scikit-learn

joblib

Install the required libraries using pip:

bash
Copy
Edit
pip install pandas scikit-learn joblib
Getting Started
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Suchint99/load-save-model.git
cd load-save-model
Launch Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Run the Notebooks:

Open Creating_And_Saving_Model.ipynb and execute the cells to train and save the model.

Open Loading_And_Using_The_Model.ipynb and execute the cells to load the saved model and perform predictions.

Project Overview
The project follows these steps:

Data Loading: Reads the dataset from train.csv.

Data Preprocessing: Handles missing values, encodes categorical variables, and splits the data into training and testing sets.

Model Training: Trains a machine learning model (e.g., Logistic Regression) on the training data.

Model Saving: Saves the trained model to the Loan_Model/ directory using joblib.

Model Loading: Loads the saved model from disk.

Prediction: Uses the loaded model to make predictions on new or test data.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

License
This project is open-source and available under the MIT License.

