# Employee Churn Prediction Project

This project is a machine learning analysis to predict employee churn for a fictional car manufacturer company. The goal is to identify employees who are likely to leave, allowing the company to take preventative action.

## Project Structure

-   `/notebooks/Salifort_project_predictive_model.ipynb`: The main Jupyter Notebook containing all data cleaning, exploratory data analysis (EDA), feature engineering, and model building.
-   `/data/HR_capstone_dataset.csv`: A small, anonymized sample of the data used for this project.
-   `requirements.txt`: A list of all Python libraries required to run the notebook.

## Analysis and Methodology

1.  **Data Cleaning:** Handled missing values and corrected data types.
2.  **Exploratory Data Analysis (EDA):** Visualized key features to understand their relationship with churn.
3.  **Feature Engineering:** Created new features like 'tenure_in_years' and 'average_monthly_charges'.
4.  **Modeling:** Trained and compared several classification models, including Logistic Regression, Random Forest, and XGBoost.
5.  **Evaluation:** The final XGBoost model achieved an F1-score of 0.82 and an ROC-AUC of 0.88 on the test set.

## How to Run This Project

1.  Clone this repository:
    ```bash
    git clone [https://github.com/EzeChiappero/employee-churn-prediction-project.git](https://github.com/EzeChiappero/employee-churn-prediction-project.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd employee-churn-prediction-project
    ```
3.  (Optional but recommended) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Mac/Linux
    .\venv\Scripts\activate   # On Windows
    ```
4.  Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
5.  Open the Jupyter Notebook to view the analysis:
    ```bash
    jupyter notebook notebooks/Salifort_project_predictive_model.ipynb
    ```