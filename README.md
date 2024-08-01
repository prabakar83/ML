# ML
 Profit Prediction using Multiple Linear Regression
This repository contains a Python project that implements a Multiple Linear Regression model to predict the profit of startups based on their R&D Spend, Administration cost, Marketing Spend, and State. The project utilizes libraries like pandas, scikit-learn, and numpy for data preprocessing, model training, and prediction. Additionally, a simple graphical user interface (GUI) is built using tkinter to allow users to input values and obtain profit predictions interactively.

Features
Data Preprocessing: The dataset (50_Startups.csv) is preprocessed using pandas for easy manipulation and LabelEncoder from scikit-learn to convert categorical data (State) into numerical format.
Model Training: A Multiple Linear Regression model is trained using scikit-learn's LinearRegression class.
Prediction: The model can predict the profit for a startup based on the input features.
GUI: A user-friendly interface built with tkinter allows users to input data (R&D Spend, Administration cost, Marketing Spend, and State) and predict the corresponding profit.
Model Serialization: The trained model is serialized using Python's pickle module, enabling the model to be saved and loaded for future predictions without retraining.


How to Run
Install Dependencies:

Ensure you have Python installed (preferably 3.7 or above).
Install the required libraries using pip
pip install pandas scikit-learn numpy

Dataset:
Ensure the 50_Startups.csv file is in the specified directory, or update the path in the script accordingly.
Train the Model:

Run the script to train the model and save it using pickle.
Run the GUI Application:


python script_name.py
Enter the values for R&D Spend, Administration cost, Marketing Spend, and select the State from the dropdown menu.
Click "Submit" to get the predicted profit.
Project Structure
50_Startups.csv: The dataset used for training the model.
script_name.py: The main script that includes data preprocessing, model training, and GUI implementation.
multilinear.pkl: The serialized model file saved after training.
