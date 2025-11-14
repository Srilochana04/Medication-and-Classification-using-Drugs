# Medication-and-Classification-using-Drugs
This project focuses on building a system for medication analysis and drug classification using machine learning and structured drug-related datasets. The goal is to assist researchers, healthcare students, and developers in understanding how medications can be categorized based on their attributes, effects, and clinical properties.

Project Overview

This application uses a drug dataset (drug2002.csv) and performs preprocessing, scaling, and classification to predict the correct drug type.
A Tkinter-based graphical interface makes it easy for users to enter patient details and get instant predictions.

✔ Key Features

Machine Learning classification using KNN algorithm

Clean Tkinter GUI

Inputs:

Age

Sex

Blood Pressure (BP)

Cholesterol

Na_to_K (Sodium-to-Potassium ratio)

Displays predicted drug class:
drugA, drugB, drugC, drugX, DrugY

"Clear" and "Quit" functionality

Dataset preprocessing:

Encoding categorical variables

Feature scaling with StandardScaler

Train-test split

Background image support for enhanced UI

🛠 Technologies Used

Python

Tkinter – GUI

Pandas – Data handling

Scikit-learn

KNN Classifier

Train/Test Split

StandardScaler

PIL (Pillow) – Image handling

📂 How It Works

Loads the dataset (drug2002.csv)

Maps categorical text fields (Sex, BP, Cholesterol)

Splits into training and testing sets

Scales features using StandardScaler

Trains a KNN model (k=1, Euclidean distance)

Takes user input from Tkinter GUI

Predicts drug category

Displays the result on screen

🖼 GUI Preview

The interface includes:

Input fields for all parameters

Predict, Clear, and Quit buttons

Display area for predicted drug

Optional background image (drug1.jpg)

📁 Files Required

drug2002.csv – Dataset

drug1.jpg – Background image

Main Python script (your code)
