# Heart-Prediction-and-Analysis-App
This project is a web-based application that predicts the risk of heart attack based on user input and relevant health metrics. It leverages machine learning algorithms to provide users with personalized risk assessments and recommendations for maintaining heart health.

## Installation Instructions

Follow these steps to set up and run the Heart Attack Prediction and Analysis App locally:

1. Clone the repository

2. Download CSV file and the project file

3. Navigate to the project directory

4. Install dependencies:
pip install -r requirements.txt

5. Run the .py file: 
A pickle file will be procured.
Load the pickle file into the project directory.
Make alterations to the front end as desired.
Specify the CSV path according to the path given in the respective system (this will usually be present in the downloads folder).

4. Run the application:
python manage.py runserver

## Usage Guidelines

To use the Heart Attack Prediction and Analysis App:

1. Open your web browser and navigate to the URL that typically appears as http://localhost:5000.

2. This navigates to the Data tab which gives essential information of the dataset such as the first and last few rows

  The Descriptive statistics gives the descriptive statistical summary of the dataset.
  The Exploratory Data Analysis tab displays the dynamic visualisation of the dataset and its variables.
  The Data Profile tab gives the data profile report of the dataset.
  The Predict tab allows to predict the heart attack risk with the user inputted variables.

3. Fill out the input form with relevant health metrics, including age, gender, height, weight, sleep hours etc.

4. Click the "Predict" button to obtain a personalized risk assessment for heart disease.

5. Review the results and any accompanying recommendations provided by the app.


Note: This application is for informational purposes only and should not be considered a substitute for professional medical advice.
