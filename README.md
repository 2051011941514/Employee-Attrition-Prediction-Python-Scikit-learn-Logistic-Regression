# Employee Attrition Prediction

## Project Overview

Employee attrition is a major challenge for organizations because employee turnover can affect productivity, increase recruitment costs, and disrupt team performance.

This project uses Python and Machine Learning to analyze employee data and predict which employees may be at risk of leaving an organization. A Logistic Regression model is developed using the IBM HR Analytics dataset to support data-driven HR decisions.

## Business Problem

Organizations need to understand the factors associated with employee attrition to make informed workforce decisions. This project explores employee data to identify potential attrition patterns and build a predictive model that can help HR teams identify employees who may require further attention.

## Project Objectives

* Analyze employee data to understand attrition patterns.
* Clean and preprocess the dataset for machine learning.
* Perform Exploratory Data Analysis (EDA) to investigate workforce trends.
* Build a Logistic Regression model to predict employee attrition.
* Evaluate model performance using relevant classification metrics.
* Identify how predictive analytics can support HR decision-making.

## Tools and Technologies

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Machine Learning Algorithm:** Logistic Regression
* **Techniques:** Data Cleaning, Exploratory Data Analysis, Categorical Encoding, Feature Preprocessing
* **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix

## Dataset

This project uses the IBM HR Analytics Employee Attrition dataset.

The dataset contains employee-related information that can be analyzed to investigate patterns associated with employee attrition.

Key features may include employee age, department, job role, job satisfaction, monthly income, overtime, and attrition status.

*Note: Confirm the dataset source and actual features against the dataset used in your notebook.*

## Project Workflow

1. **Data Loading:** Load the employee dataset and inspect its structure.
2. **Data Cleaning:** Check data quality and prepare the dataset for analysis.
3. **Exploratory Data Analysis:** Explore employee characteristics and attrition patterns.
4. **Data Preprocessing:** Apply categorical encoding and feature preprocessing.
5. **Model Building:** Train a Logistic Regression model using Scikit-learn.
6. **Model Evaluation:** Evaluate the model using a confusion matrix, accuracy, precision, recall, and F1-score.
7. **Business Interpretation:** Consider how the findings could support workforce planning and employee retention initiatives.

## Model Performance

The Logistic Regression model achieved the following results in this project:

| Evaluation Metric | Result |
| ----------------- | -----: |
| Accuracy          |    72% |
| Recall            |    77% |

Accuracy measures the proportion of correct predictions, while recall measures how many actual attrition cases the model correctly identifies.

These results should be interpreted alongside precision, F1-score, and the confusion matrix to better understand the model's strengths and limitations.

## Business Value

The project demonstrates how data analytics and machine learning can support workforce planning and employee retention.

Potential business applications include:

* Identifying employee groups that may need further investigation.
* Supporting HR teams in analyzing attrition patterns.
* Helping organizations make more informed workforce decisions.
* Using data-driven insights to guide employee retention strategies.

Model predictions should be treated as indicators for further analysis rather than definitive conclusions about individual employees.

## Project Structure

```text
employee-attrition-prediction/
│
├── README.md
├── employee_attrition_prediction.ipynb
└── data/
    └── README.md
```

*Update this structure to match the files actually uploaded to your repository.*

## How to Run the Project

1. Clone or download this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries.
4. Open the notebook and run the cells in sequence.

Install the core libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Conclusion

This project demonstrates the application of data analysis and machine learning to an HR business problem. By combining exploratory analysis, data preprocessing, and Logistic Regression, it illustrates how employee data can be used to investigate attrition patterns and support data-informed workforce decisions.

## Author

**Tejas Kokade**

MBA – Data Science & Business Analytics

