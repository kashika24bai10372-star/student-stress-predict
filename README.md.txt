# Student Stress Prediction – Machine Learning Project

Overview
This project predicts student stress levels using machine learning techniques.  
The model is trained on various student lifestyle and academic factors such as:
- Study hours  
- Sleep duration  
- Academic pressure  
- Physical activity  
- Social support  
- Health and personal habits  

The goal of the project is to identify stress level (Low, Medium, High) and help students become aware of their mental health patterns.


Project Structure
The repository contains the following files and folders:

- *dataset/*  
  Contains the dataset used for training and testing.

- *code/*  
  Python scripts and Jupyter notebooks for data preprocessing, model training, and prediction.

- *screenshots/*  
  Screenshots of model training, output, and results.

- *recordings/*  
  (Optional) Screen recordings showing project execution.

- *project_report.pdf*  
  Official PDF report submitted for the VITyarthi flipped course project.

- *README.md*  
  Project documentation.

Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook / VS Code  

 Model Details
A RandomForestClassifier model is used because:
- It handles categorical + numerical data well  
- It is stable against overfitting  
- It provides high accuracy  

Output Categories:
- 0 → Low Stress
- 1 → Medium Stress
- 2 → High Stress

How the System Works
1. Load and clean the dataset  
2. Perform preprocessing (handling missing values, encoding, scaling)  
3. Train Random Forest model  
4. Evaluate using accuracy score  
5. Predict stress level for new student data  

Results
The model achieves good accuracy on test data and provides interpretable results showing which features impact stress levels most.

 Author
PARV AGRAWAL  
Registration No:25MIM10225  
email id: parv.25mim10225@vitbhopal.ac.in
VIT Bhopal University  
