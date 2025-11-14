# Medication-and-Classification-using-Drugs
This project focuses on building a system for medication analysis and drug classification using machine learning and structured drug-related datasets. The goal is to assist researchers, healthcare students, and developers in understanding how medications can be categorized based on their attributes, effects, and clinical properties.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Drug Classification using Machine Learning & Tkinter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eef7ff;
            margin: 0;
            padding: 20px;
            line-height: 1.7;
        }
        h1, h2, h3 {
            color: #045c8c;
        }
        .container {
            width: 90%;
            margin: auto;
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(0,0,0,0.1);
        }
        code, pre {
            background: #f4f4f4;
            padding: 10px;
            display: block;
            border-radius: 5px;
            overflow-x: auto;
        }
        ul {
            padding-left: 20px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            color: gray;
        }
    </style>
</head>

<body>

<div class="container">
    <h1>🧪 Drug Classification using Machine Learning & Tkinter GUI</h1>
    <p>
        This project is a <strong>Drug Classification System</strong> built using 
        <strong>Python</strong>, <strong>Tkinter</strong>, and a 
        <strong>K-Nearest Neighbors (KNN) machine learning model</strong>.
        It allows users to input patient information and predicts the appropriate drug class.
    </p>

    <hr>

    <h2>🚀 Project Overview</h2>
    <p>
        The program uses the <strong>drug2002.csv</strong> dataset and performs preprocessing, 
        encoding, scaling, and classification. A user-friendly <strong>Tkinter GUI</strong> 
        lets users enter their details and get instant predictions.
    </p>

    <h3>✔ Key Features</h3>
    <ul>
        <li>Machine Learning classification using <strong>KNN</strong> algorithm</li>
        <li>Simple and clear <strong>Tkinter GUI</strong></li>
        <li>Input fields:
            <ul>
                <li>Age</li>
                <li>Sex</li>
                <li>Blood Pressure (BP)</li>
                <li>Cholesterol</li>
                <li>Na_to_K</li>
            </ul>
        </li>
        <li>Displays predicted drug class: <strong>drugA</strong>, <strong>drugB</strong>, <strong>drugC</strong>, <strong>drugX</strong>, <strong>DrugY</strong></li>
        <li>Clear & Quit button functionality</li>
        <li>Background image support</li>
    </ul>

    <hr>

    <h2>🛠 Technologies Used</h2>
    <ul>
        <li><strong>Python</strong></li>
        <li><strong>Tkinter</strong> for GUI</li>
        <li><strong>Pandas</strong> for data handling</li>
        <li><strong>Scikit-learn</strong> (KNN, Train/Test Split, StandardScaler)</li>
        <li><strong>PIL (Pillow)</strong> for image processing</li>
    </ul>

    <hr>

    <h2>📂 How It Works</h2>
    <ol>
        <li>Loads dataset (<strong>drug2002.csv</strong>)</li>
        <li>Encodes categorical features (Sex, BP, Cholesterol)</li>
        <li>Splits data into training/testing</li>
        <li>Scales features with <strong>StandardScaler</strong></li>
        <li>Trains a <strong>K=1 KNN model</strong></li>
        <li>Takes user inputs from GUI</li>
        <li>Predicts drug class</li>
        <li>Displays results on screen</li>
    </ol>

    <hr>

    <h2>🖼 GUI Overview</h2>
    <p>The GUI contains:</p>
    <ul>
        <li>Input fields for patient details</li>
        <li>Predict button</li>
        <li>Clear button</li>
        <li>Quit confirmation window</li>
        <li>Background image (<strong>drug1.jpg</strong>)</li>
    </ul>

    <hr>

    <h2>📁 Required Files</h2>
    <ul>
        <li><strong>drug2002.csv</strong> – Dataset</li>
        <li><strong>drug1.jpg</strong> – Background image</li>
        <li><strong>Main Python script</strong></li>
    </ul>

    <hr>

    <h2>▶ Running the Program</h2>
    <pre><code>
python your_script_name.py
    </code></pre>

    <p>Ensure the following files are in the same folder:</p>
    <pre><code>
drug2002.csv
drug1.jpg
your_script.py
    </code></pre>

    <hr>

    <h2>📌 Future Improvements</h2>
    <ul>
        <li>Display accuracy score</li>
        <li>Use advanced ML models (Random Forest, SVM, etc.)</li>
        <li>Add dropdown menus instead of text entries</li>
        <li>Error handling for invalid inputs</li>
    </ul>

</div>

<footer>
    <p>© 2024 Drug Classification Project – Machine Learning + Tkinter GUI</p>
</footer>

</body>
</html>

