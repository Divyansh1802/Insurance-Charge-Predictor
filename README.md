# Insurance Charge Prediction using Linear Regression

This project focuses on predicting medical insurance charges using a Linear Regression machine learning model. 
The model estimates insurance costs based on personal and demographic attributes.

------------------------------------------------------------

## Project Overview

Medical insurance costs depend on multiple factors such as age, BMI, smoking habits, and region. 
The objective of this project is to build a regression model that accurately predicts insurance charges using these features.

This is a supervised learning regression problem where the target variable (charges) is continuous.

------------------------------------------------------------

## Dataset Information

The dataset used in this project is `insurance.csv`, which contains the following features:

- age       : Age of the policyholder  
- sex       : Gender (male/female)  
- bmi       : Body Mass Index  
- children  : Number of dependents  
- smoker    : Smoking status (yes/no)  
- region    : Residential region (northeast, northwest, southeast, southwest)  
- charges   : Medical insurance cost (Target Variable)

------------------------------------------------------------

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

------------------------------------------------------------

## Project Workflow

1. Data Loading
2. Data Exploration and Analysis
3. Data Preprocessing
   - Encoding categorical variables
   - Feature selection
4. Train-test split
5. Model training using Linear Regression
6. Model evaluation
7. Prediction of insurance charges

------------------------------------------------------------

## Model Evaluation Metrics

The model performance was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

These metrics measure how accurately the model predicts insurance charges.

------------------------------------------------------------

## How to Run the Project

1. Clone the repository:

    git clone https://github.com/Divyansh1802/Insurance-Charge-Predictor.git

2. Navigate to the project folder:

    cd Insurance-Charge-Predictor

3. Install required dependencies:

    pip install -r requirements.txt

4. Open the Jupyter Notebook and run all cells.

------------------------------------------------------------

## Example Prediction

Input:
- Age: 30  
- Sex: Male  
- BMI: 25.3  
- Children: 1  
- Smoker: No  
- Region: Southeast  

Output:
- Predicted Insurance Charges: (Model Generated Value)

------------------------------------------------------------

## Future Improvements

- Apply advanced regression models (Random Forest, Gradient Boosting, XGBoost)
- Perform hyperparameter tuning
- Deploy the model using Flask or Streamlit
- Build a user-friendly interface for real-time predictions

------------------------------------------------------------

## Author

Divyansh Upadhyay
