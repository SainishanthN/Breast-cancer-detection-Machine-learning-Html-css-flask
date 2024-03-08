Breast Cancer Detection

This repository contains a Flask web application for detecting breast cancer using machine learning. The application allows users to input various features related to breast cancer tumors and predicts whether the tumor is severe or not.

Features:

Predicts breast cancer severity based on input features such as mean radius, mean perimeter, mean area, mean compactness, mean concavity, mean concave points, radius error, perimeter error, area error, worst radius, worst perimeter, worst area, worst compactness, worst concavity, and worst concave points.
Libraries Used:

Flask: For creating the web application.
NumPy: For numerical computations.
Pandas: For data manipulation and analysis.
Scikit-learn: For machine learning tasks.
Flask: For web development.
Setup:

Clone the repository:

bash
Copy code
git clone https://github.com/<username>/breast-cancer-detection.git
Install the required dependencies:

Copy code
pip install -r requirements.txt
Run the Flask application:

Copy code
python app.py
The application will be accessible at http://localhost:5000 in your web browser.

Usage:

Navigate to the home page (/) to access the main interface.
Input the required features related to the breast tumor.
Click the "Predict" button to view the prediction result.
Files:

app.py: Contains the Flask application code.
templates/: Contains HTML templates for rendering the web pages.
Contributing:

Contributions to the project are welcome. You can contribute by:

Reporting bugs
Fixing issues
Adding new features
Improving documentation
License:

This project is licensed under the MIT License. You are free to use, modify, and distribute the code for both commercial and non-commercial purposes. See the LICENSE file for details.
