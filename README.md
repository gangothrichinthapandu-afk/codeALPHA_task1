# Credit Score Prediction Using Machine Learning

## 📌 Project Overview

This project predicts an individual's **creditworthiness** using historical financial information and machine learning techniques.

The model analyzes factors such as income, debt, payment history, credit utilization, and other financial attributes to classify whether a person is likely to have **good or poor creditworthiness**.

## 🎯 Objective

The main objective of this project is to build a machine learning model that can:

* Predict creditworthiness from financial data.
* Identify important factors affecting credit scores.
* Compare different classification algorithms.
* Evaluate model performance using standard classification metrics.

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data processing
* **NumPy** – Numerical operations
* **Scikit-learn** – Machine learning
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Google Colab / Jupyter Notebook**

## 📊 Dataset

The dataset contains financial information about individuals.

### Example Features

| Feature                 | Description                               |
| ----------------------- | ----------------------------------------- |
| `income`                | Annual income of the individual           |
| `debt`                  | Total outstanding debt                    |
| `credit_utilization`    | Percentage of available credit being used |
| `payment_history`       | Record of timely/late payments            |
| `credit_history_length` | Length of credit history                  |
| `number_of_accounts`    | Number of credit accounts                 |
| `creditworthiness`      | Target variable                           |

> **Note:** The exact features depend on the dataset used for training.

## 🤖 Machine Learning Algorithms

The project can use multiple classification algorithms:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

These models are trained and compared to determine which performs best on the dataset.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Prediction
   ↓
Model Evaluation
   ↓
Best Model Selection
```

## 📈 Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix

### Metrics

**Precision:** Measures how many predicted positive cases were actually positive.

**Recall:** Measures how many actual positive cases were correctly identified.

**F1-Score:** Provides a balance between precision and recall.

**ROC-AUC:** Measures how well the model distinguishes between different classes.

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/credit-score-prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd credit-score-prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 4. Run the Notebook

Open the `.ipynb` file using:

* Google Colab
* Jupyter Notebook
* VS Code

### 5. Upload the Dataset

Place your CSV dataset in the project directory and update the dataset path in the Python code if required.

## 📁 Project Structure

```text
credit-score-prediction/
│
├── credit_score_prediction.ipynb
├── credit_score_dataset.csv
├── README.md
└── requirements.txt
```

## 💡 Results

After training and evaluating the models, the model with the best evaluation performance can be selected for predicting creditworthiness.

The results can be visualized using:

* Confusion Matrix
* ROC Curve
* Feature Importance
* Model Performance Comparison

## 🔮 Future Improvements

* Use larger real-world financial datasets.
* Apply advanced feature engineering.
* Try Gradient Boosting, XGBoost, or other ensemble models.
* Build a web application for real-time prediction.
* Improve model interpretability using explainable AI techniques.
* Deploy the model using Flask, FastAPI, or Streamlit.

## 👩‍💻 Author

**Gangothri**

B.Tech – Artificial Intelligence and Machine Learning

## 📄 License

This project is created for **educational and academic purposes**.
