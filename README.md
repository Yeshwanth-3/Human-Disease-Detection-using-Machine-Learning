# Human-Disease-Detection-using-Machine-Learning
This is a Python desktop application that predicts diseases based on selected symptoms using machine learning algorithms. Built with Tkinter for the user interface and trained on a medical dataset, the system uses Decision Tree, Random Forest, and Naive Bayes classifiers to make accurate predictions.

📌 Features
-GUI built with Tkinter for easy interaction
-Users can select up to 5 symptoms from a dropdown menu
-Predicts disease using three different ML models
-Displays results instantly in the GUI
-Accuracy scores printed for each model using test data

🛠️ Technologies Used
-Python
-Tkinter – for the GUI
-Pandas & NumPy – for data processing
-Scikit-learn – for training ML models
-CSV files – for training and testing data

📂 Dataset
-Training.csv – used to train the machine learning models
-Testing.csv – used to evaluate model accuracy
-Each row contains symptoms as binary features and a corresponding disease label

🚀 How to Run
Install dependencies (if not already installed):
->pip install pandas numpy scikit-learn

Ensure you have the required files:
--Training.csv
--Testing.csv

Run the application:
->python your_script_name.py
---Use the GUI to enter patient symptoms and view predictions.

🤖 Machine Learning Models Used
-Decision Tree Classifier
-Random Forest Classifier
-Naive Bayes Classifier
-Each model is trained on the Training.csv dataset and makes predictions based on user-inputted symptoms.

📊 Output
-Displays predicted disease for each model in the GUI
-Prints model accuracy scores in the terminal

👨‍⚕️ Example Use Case
-Enter patient name.
-select 5 symptoms from dropdowns.
-Click any of the model buttons (e.g., Decision Tree).
-View the predicted disease in the output box.
