# Medication-and-Classification-using-Drugs

This project focuses on building a system for medication analysis and drug classification using
machine learning and structured drug-related datasets. The goal is to assist researchers,
healthcare students, and developers in understanding how medications can be categorized
based on their attributes, effects, and clinical properties.

## KEY FEATURES
- Machine Learning classification using KNN  
- Tkinter-based GUI interface  
- Input fields: Age, Sex, Blood Pressure, Cholesterol, Na_to_K  
- Predicts drug categories: drugA, drugB, drugC, drugX, DrugY  
- Includes Predict, Clear, and Quit buttons  
- Background image support  
- Dataset preprocessing and feature scaling  

## TECHNOLOGIES USED
- Python  
- Tkinter (GUI)  
- Pandas (Data Processing)  
- Scikit-learn  
  - KNN Classifier  
  - Train/Test Split  
  - StandardScaler  
- Pillow (PIL) for image handling  

## HOW THE SYSTEM WORKS
1. Loads and reads the dataset (drug2002.csv).  
2. Maps categorical values such as Sex, BP, and Cholesterol into numerical form.  
3. Splits data into training and testing sets.  
4. Scales the dataset using StandardScaler.  
5. Trains a KNN model (k = 1).  
6. Accepts user inputs through the Tkinter GUI.  
7. Predicts the drug category based on the model.  
8. Displays the prediction on the screen.  

## GUI DESCRIPTION
The GUI includes:
- Input fields for all features  
- Predict button to generate output  
- Clear button to reset the fields  
- Quit button to exit the application  
- Background image (drug1.jpg)  

## REQUIRED FILES
- drug2002.csv – Dataset  
- drug1.jpg – Background image  
- Main Python script  

## HOW TO RUN THE PROGRAM
Run the Python script using:

