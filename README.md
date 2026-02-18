# Loan Approval System

## Overview

The **Loan Approval System** is a web-based application that predicts loan eligibility using a machine learning model. The system is designed to demonstrate the integration of machine learning with a Flask-based web application and to provide essential financial utilities such as bank information and EMI calculation. This project follows a clean and modular structure suitable for academic and professional demonstration purposes.

---

## Key Features

* **Loan Eligibility Prediction**

  * Predicts whether a loan is likely to be approved
  * Uses a trained **Random Forest Classifier**

* **Bank Information Module**

  * Categorized list of Government and Private banks
  * Static data stored using Python dictionaries

* **EMI Calculator**

  * Calculates monthly EMI based on loan amount, interest rate, and tenure

* **Guidance Pages**

  * Loan guide for basic understanding
  * About and Contact pages for project information

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask

### Machine Learning

* Scikit-learn
* Random Forest Algorithm
* Pandas
* NumPy

---

## Project Structure

* Quick note - Files not actually used for the website but, were created and were deemed useful are not included in the below structure but do exist in the folder.

```
Loan-Approval-System/
│
├── app.py                  # Main Flask application
├── model.pkl               # Trained machine learning model
├── requirements.txt        # Python dependencies
│
├── templates/              # HTML templates
│   ├── index.html
│   ├── predict.html
│   ├── banks.html
│   ├── emi.html
│   ├── guide.html
│   ├── about.html
│   └── contact.html
│
├── static/                 # Static assets
│   ├── css/
│   └── js/
│
└── README.md               # Project documentation
```

---

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Mohit-Bhole/Loan-management-System.git
   ```

2. Navigate to the project directory:

   ```bash
   cd loan-approval-system
   ```

3. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   python app.py
   ```

5. Access the application in your browser:

   ```
   http://127.0.0.1:5000/
   ```

---

## Machine Learning Model

* **Algorithm:** Random Forest Classifier
* **Model File:** `model.pkl`
* **Purpose:** Predict loan approval status based on user inputs

The model is pre-trained and loaded at runtime to generate predictions.

---

## Use Case

* Academic Mini or Major Project
* Demonstration of ML and Flask integration
* Learning full-stack machine learning application development

---

## Future Enhancements

* Database integration
* User authentication and authorization
* Dynamic bank data
* Model optimization and evaluation metrics
* Cloud deployment

---

---

## Screenshots
![Home-page](https://github.com/Mohit-Bhole/Loan-management-System/blob/cfad2f3265edc40bb69ea2ac04a67cf589d2a19c/Screenshot%202025-12-20%20132027.png)
![Predict-page](https://github.com/Mohit-Bhole/Loan-management-System/blob/cfad2f3265edc40bb69ea2ac04a67cf589d2a19c/Screenshot%202025-12-20%20132208.png)
![Banks-page](https://github.com/Mohit-Bhole/Loan-management-System/blob/cfad2f3265edc40bb69ea2ac04a67cf589d2a19c/Screenshot%202025-12-20%20132438.png)
![Calculate-Emi-page](https://github.com/Mohit-Bhole/Loan-management-System/blob/cfad2f3265edc40bb69ea2ac04a67cf589d2a19c/Screenshot%202025-12-20%20132543.png)
![Guide-page](https://github.com/Mohit-Bhole/Loan-management-System/blob/cfad2f3265edc40bb69ea2ac04a67cf589d2a19c/Screenshot%202025-12-20%20132616.png)

---

## License

This project is intended for educational purposes only.
