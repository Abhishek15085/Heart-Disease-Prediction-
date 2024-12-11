

# Heart Disease Prediction using Machine Learning

This project is aimed at creating a machine learning-based solution for early detection of heart disease. The goal is to empower healthcare professionals and individuals by providing a user-friendly tool to assess heart disease risk using key medical data.


## Features
- **Web Application**: A user-friendly portal developed using Flask.
- **Machine Learning Models**: 
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest (93% accuracy)
  - K-Nearest Neighbors (KNN)
- **Key Functionalities**:
  - Input medical data like age, cholesterol, and blood pressure.
  - Receive risk predictions (low, medium, or high).
  - Download a detailed PDF report of the results.


## Dataset
- **Source**: Public dataset from Kaggle, originally processed from UCI's dataset.
- **Attributes**: 13 medical features such as cholesterol levels, blood pressure, and more, with a target label indicating heart disease presence.


## Technologies Used
- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Libraries**:
  - NumPy, Pandas for data manipulation
  - Matplotlib for visualizations
  - Scikit-learn for model building

## How It Works
1. **Input Data**: Users enter health-related information through a simple web form.
2. **Backend Processing**: Data is processed by the Random Forest model for prediction.
3. **Output**: Risk levels are displayed, and users can download a detailed report.


## Results
- **Random Forest**: Achieved the highest accuracy of 93%.
- Other model performances:
  - Logistic Regression: 85%
  - SVM: 79%
  - Decision Tree: 75%
  - KNN: 75%

## Future Enhancements
- Reduce required attributes for prediction to simplify input.
- Experiment with additional machine learning algorithms to improve accuracy.
- Deploy the application for real-world usage.

