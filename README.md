# 🧠 Employee Salary Prediction using Machine Learning

This project uses supervised machine learning techniques to predict whether an individual's annual income exceeds $50K based on demographic and employment-related features.

---

## 📌 Problem Statement

Given a dataset containing attributes like age, education level, occupation, and working hours, the task is to build a classification model that can predict whether a person earns:

- `<=50K`  
- `>50K`

---

## 🛠️ Tech Stack

- Python 3.8+
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn (for visualization)
- scikit-learn (Logistic Regression, Random Forest, Gradient Boosting, etc.)
- StandardScaler, LabelEncoder / OneHotEncoder
- joblib (for saving the trained model) *(optional)*

---

## 📁 Project Structure

<pre>
employee-salary-prediction/
├── employee_data.csv # Dataset used
├── salary_prediction.ipynb # Main Jupyter notebook (EDA, preprocessing, ML models)
├── .gitignore # Git ignore file
└── README.md # Project documentation
</pre>

---

## 🚀 How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/employee-salary-prediction.git
   cd employee-salary-prediction

2. **(Optional) Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate      # On Windows: venv\Scripts\activate

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   Or
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. **Run the notebook**
   Open ```Salary_Prediction.ipynb``` in Jupyter or VS Code and run all cells step-by-step.
  
