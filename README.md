# loan-eligibility-prediction

Classification project to predict whether a loan applicant is eligible for loan approval based on their demographic, financial, and credit history information.

## Dataset

- Files: `loantrain.csv`, `loantest.csv`  
- Source: [Loan Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)  
- Description:
  - `loantrain.csv` contains labeled data (Loan_Status = Y/N)  
  - `loantest.csv` is used for generating final predictions  
- Target variable: `Loan_Status` (1 = Approved, 0 = Rejected)

## Tools and Libraries

- Python  
- Jupyter Notebook  
- pandas, numpy  
- seaborn, matplotlib  
- scikit-learn

## Project Structure

loan-eligibility-prediction  
- loantrain.csv  
- loantest.csv  
- loan_eligibility_prediction.ipynb  
- README.md  
- requirements.txt  

## Exploratory Data Analysis (EDA)

- Loan approval rates across different education levels and property areas  
- Distribution of applicant income and loan amount  
- Loan approval vs applicant financial factors  
- Visualized relationships using count plots, histograms, and box plots

## Preprocessing

- Handled missing values in categorical and numerical columns  
- Label encoded categorical variables for modeling  
- Split train data into training and validation sets

## Model Used

- Logistic Regression (Best Performing Model)  

## Evaluation

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

Example validation result:
Validation Accuracy: 0.7886178861788617


## Final Prediction

- Trained final model on full data  
- Predicted on test dataset (`loantest.csv`)  
- Submission-ready DataFrame generated with `Loan_ID` and predicted `Loan_Status`

## How to Run

1. Clone this repository  
2. Download `loantrain.csv` and `loantest.csv` from Kaggle and place them in the project folder  
3. Open `loan-eligibility-prediction.ipynb` in Jupyter Notebook or Google Colab  
4. Run all cells in order  

## Author

Talasila Navya Annapurna  

GitHub: https://github.com/NavyaTalasila5  

LinkedIn: https://www.linkedin.com/in/navya-talasila-3134a1325/

