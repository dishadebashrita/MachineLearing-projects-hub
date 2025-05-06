# 🧠 Employee Mental Health Prediction using Machine Learning

This project explores the application of machine learning algorithms to predict mental health treatment needs based on employee survey data. It uses two datasets: `employee_train.csv` and `employee_test.csv`, containing responses related to age, gender, work environment, and mental health history.

---

## 📁 Datasets Used

- `employee_train.csv` – Training dataset for model development.
- `employee_test.csv` – Unseen test dataset for model validation.

### 📊 Features include:
| Feature | Description |
|---------|-------------|
| Timestamp | Submission time of the survey |
| Age | Age of the respondent |
| Gender | Gender identity |
| Country / State | Location of the respondent |
| Self Employed | Whether respondent is self-employed |
| Family History | Family history of mental illness |
| Treatment | Whether they have sought treatment for mental health |
| Work Interfere | How mental health interferes with work |
| No. of Employees | Company size |
| Remote Work | Remote work allowed or not |
| Tech Company | Whether company is a tech company |
| Benefits | Availability of mental health benefits |
| Care Options | Availability of care options |
| Wellness Program | Existence of wellness programs |
| Seek Help | Ease of seeking help |
| Anonymity | Anonymity policies |
| Leave | Mental health leave policies |
| Mental/Physical Health Consequences | Perceived consequences of disclosure |
| Coworkers / Supervisor | Comfort discussing mental health |
| Interviews / Observed Consequences | History of interviews or observed consequences |
| Comments | Optional comments section |

---

## ⚙️ Machine Learning Models Applied

We explored and compared several supervised learning algorithms:

- **Linear Regression**
- **Random Forest**
- **Logistic Regression**
- **Decision Tree**
- **Support Vector Machine (SVM)**

### 🧪 Key Steps Performed:

1. **Data Preprocessing**
   - Missing value treatment
   - Label encoding for categorical variables
   - Outlier handling
   - Feature selection

2. **Exploratory Data Analysis (EDA)**
   - Distribution plots
   - Correlation heatmaps
   - Value counts and bar plots for categorical features

3. **Model Training & Evaluation**
   - Train-test split
   - Cross-validation
   - Evaluation using metrics like accuracy, precision, recall, F1-score

4. **Predictions on Test Data**
   - Final model applied to test dataset
   - Output predictions generated

---

## 📈 Objective

To predict whether an employee is likely to seek mental health **treatment** based on demographic and workplace factors. This can help organizations create better support systems and identify at-risk employees early.

---

## 💻 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Use of ensemble methods like XGBoost
- Deployment as a Flask web application
- Better handling of class imbalance

---


