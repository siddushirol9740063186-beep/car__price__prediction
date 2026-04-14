Car Price Prediction 🚗

This project is a Machine Learning web application that predicts the resale price of used cars based on user inputs such as year, fuel type, kilometers driven, and more. The application is built using Python and deployed using Streamlit for an interactive user interface.

Project Overview

The goal of this project is to build a predictive model that estimates car prices using historical data. The model is trained on the CarDekho dataset and uses regression techniques to provide accurate predictions.

Technologies Used

Python
Pandas
NumPy
Scikit-learn
Streamlit

Features

Predict car resale price instantly
Simple and user-friendly interface
Fast and accurate predictions
Deployed as a web application

Project Structure

app.py → Streamlit web application
model.pkl → Trained Machine Learning model
car_data.csv → Dataset used for training
car_price_model.ipynb → Model training notebook
requirements.txt → Required libraries

How to Run the Project Locally

Step 1: Install required libraries
pip install -r requirements.txt

Step 2: Run the Streamlit app
streamlit run app.py

The app will open in your browser automatically.

How the Model Works

The dataset is preprocessed by converting categorical values into numerical format.
A new feature called Car Age is created from the year of purchase.
The data is split into training and testing sets.
A Random Forest Regressor model is trained on the dataset.
The trained model is saved as model.pkl and used in the Streamlit app for predictions.

Deployment

The project is deployed using Streamlit Cloud.
Steps followed:

Upload project files to GitHub
Connect GitHub repository to Streamlit Cloud
Select app.py as the main file
Deploy the application

Future Improvements

Add more features for better prediction accuracy
Improve UI with advanced design
Add graphs and analytics
Integrate real-time data

Developed By

Siddu Shirol
