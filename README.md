# -Revolutionizing-Liver-Care-Predicting-Liver-Cirrhosis-using-Advanced-Machine-Learning--Techniques
.

📘 Project Documentation
Title: Revolutionizing Liver Care: Predicting Liver Cirrhosis using Advanced Machine Learning Techniques
✅ Table of Contents:
Project Overview

Folder Structure

Tools & Technologies

Detailed Explanation of Folders & Files

Workflow & Integration

Output & Results

Future Scope

References

1. 🎯 Project Overview:
This project focuses on predicting liver cirrhosis using machine learning techniques integrated with a Flask web application. It involves preprocessing patient data, training ML models, saving them as .pkl files, and deploying a user-friendly interface for predictions.

2. 📁 Folder Structure:
sql
Copy code
Revolutionizing-Liver-Care/
│
├── Data/
├── Documentation/
├── Flask/
│   ├── static/
│   ├── templates/
│   │   ├── assets/
│   │   ├── forms/
│   │   ├── index.html
│   │   ├── inner-page.html
│   │   └── portfolio-details.html
│   ├── app.py
│   ├── normalizer.pkl
│   └── rf_acc_68.pkl
├── Training/
3. 🛠️ Tools & Technologies Used:
Languages: Python, HTML, CSS, JavaScript

Frameworks: Flask

Libraries: Scikit-learn, Pandas, NumPy, Pickle

ML Techniques: Random Forest Classifier

Model Artifacts: .pkl files for model and normalization

IDE/Platform: Jupyter Notebook, VS Code, SmartInternz

4. 🗂️ Detailed Explanation of Folders & Files:
🔹 Data/
Contains raw and cleaned liver patient datasets used for training and testing the model.

🔹 Documentation/
Contains reports, milestone summaries, and project explanation files.

🔹 Flask/
This is the main folder containing the web app.

static/:
Stores static files like CSS, JS, and images (e.g., for web styling).

templates/:
Contains all HTML templates used by Flask.

index.html: Main home page for user interaction.

inner-page.html: Extra information or content pages.

portfolio-details.html: Detailed insights or results display.

assets/ & forms/: Media, images, and HTML form structures.

app.py:
The core Flask application that:

Loads the ML model and normalizer (.pkl files).

Accepts form input from users.

Predicts liver cirrhosis risk.

Renders results back to the user via HTML pages.

rf_acc_68.pkl:
Trained Random Forest model with 68% accuracy, saved using pickle.

normalizer.pkl:
Scaler used for normalizing the dataset before making predictions.

🔹 Training/
Python notebooks or scripts for:

Data preprocessing

Model building

Accuracy and performance evaluation

Model export to .pkl files

5. 🔁 Workflow & Integration:
Data Preparation
Clean and preprocess liver patient data using pandas and scikit-learn.

Model Building
Train a Random Forest Classifier with evaluation metrics (accuracy, F1-score, etc.)

Model Saving
Save trained model and scaler using pickle.

Web Development with Flask

Create forms and frontend using HTML & CSS.

Connect frontend to backend via Flask routing in app.py.

Load model and normalizer to predict and display results.

6. 📊 Output & Results:
Users can input clinical parameters via a web form.

The backend predicts the likelihood of cirrhosis.

The result is shown on the HTML results page.

Model accuracy: 68% (Random Forest)

7. 🔮 Future Scope:
Improve model accuracy with more data and feature engineering.

Add more ML models and allow comparison.

Enhance UI with better design and interactivity.

Deploy on cloud platforms (Heroku, Render, etc.)

8. 📚 References:
Kaggle Liver Dataset

Scikit-learn Documentation

Flask Official Docs

SmartInternz Project Guidelines

Would you like this documentation in PDF format now?






