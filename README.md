# income-prediction
Predictive model for classifying individuals by income level.
# Income Prediction Model

This project aims to predict whether an individual earns more than $50,000 annually using a dataset of 20,000+ entries. The model leverages Logistic Regression for classification, identifying key factors like education, occupation, and age that influence income levels.

## Dataset Information
The dataset contains 20,000+ entries with features such as:
- Age
- Education
- Occupation
- Marital Status  
Dataset sourced from the [“Becker, B. & Kohavi, R. (1996). Adult [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XW20![image](https://github.com/user-attachments/assets/00c24d9f-4177-4814-ac26-12b3b7b05956)
.

## Project Workflow
1. **Data Preprocessing**:
   - Handled missing values.
   - Applied label encoding for categorical variables.
2. **Feature Engineering**:
   - Extracted key features influencing income, such as education and occupation.
3. **Model Building**:
   - Implemented Logistic Regression to classify income levels.
4. **Model Evaluation**:
   - Achieved an accuracy of 82% for predicting individuals with incomes over $50,000.

## How to Run the Project
To run this project on your local machine:
1. Clone the repository:
   ```bash
   git clone https://github.com/rugved-5631/income-prediction.git
Clone the repository:

bash
Copy code
git clone https://github.com/rugved-5631/income-prediction.git

bash
pip install pandas scikit-learn numpy matplotlib
Run the Jupyter Notebook:

bash
jupyter notebook
Open the notebook and run the cells.

Results
The model achieved an accuracy of 82% in predicting income levels. The confusion matrix and classification report are included in the results section of the Jupyter Notebook.
