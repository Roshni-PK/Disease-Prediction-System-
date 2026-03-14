# Disease Prediction and Treatment Recommendation System
A Machine Learning project demonstrating disease prediction and treatment recommendation using symptom-based analysis.

This project is a Machine Learning based web application that predicts possible diseases based on user-input symptoms and provides corresponding treatment recommendations.
The application is built using Python and Streamlit and uses a trained machine learning model to analyze symptom patterns and generate predictions.

## Features

- Predicts diseases based on symptoms
- Suggests treatment recommendations
- Interactive web interface using Streamlit
- Machine learning model trained using medical symptom dataset

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Streamlit
- Machine Learning (Random Forest Classifier)

## Project Structure

Disease-Prediction-App

train_model.py – Script used to train the machine learning model  
treatment_app.py – Streamlit web application  
disease_treatment_500.xlsx – Dataset used for training  
requirements.txt – Required Python libraries

## How to Run the Project

1. Clone the repository

git clone https://github.com/yourusername/disease-prediction-app.git

2. Navigate to the project folder

cd disease-prediction-app

3. Install dependencies

pip install -r requirements.txt

4. Train the model

python train_model.py

5. Run the application

streamlit run treatment_app.py

## Output

The application allows users to input symptoms and predicts the most likely disease along with recommended treatment options.

Note: The trained model file (.pkl) is generated automatically by running train_model.py.

## Future Improvements

- Add more diseases and symptoms to improve accuracy
- Deploy the application online
- Improve the user interface
- Integrate real-time medical datasets

## Author
Roshni Parasuraman Karunakaran
