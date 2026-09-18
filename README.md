# Machine Learning Case Studies

This repository contains my Machine Learning case studies and practice work implemented using Python and Scikit-learn.

The projects focus on understanding the complete machine learning workflow, including data preprocessing, train-test splitting, model building, evaluation, and comparison of different approaches.

## 📂 Files in This Repository

```text
Machine-Learning/
│
├── Case_Study2.ipynb
├── Case_Study1.ipynb
├── diabetic_data.csv
├── creditcard.csv
└── README.md
```

### `Case_Study2.ipynb`

This notebook contains my initial Machine Learning practice/work, including data preprocessing and model preparation.

It covers concepts such as:

* Data loading and exploration
* Data cleaning
* Feature and target separation
* Handling missing values
* Train-test split
* Data preprocessing
* Preparing data for machine learning models

### `Case_Study1.ipynb`

This notebook contains a complete case study using the **Diabetes Readmission Dataset**.

The case study includes:

* Data exploration
* Data cleaning
* Handling missing values
* Feature engineering
* Binary target creation
* Train-test splitting
* Numerical and categorical feature preprocessing
* Logistic Regression
* Logistic Regression with L2 regularization
* Model evaluation using Accuracy and AUC
* ROC curve comparison

## 📊 Dataset

The project uses the **Diabetes Readmission Dataset** stored in:

```text
diabetic_data.csv
```

The target variable is `readmitted`, which is converted into a binary classification problem.

* `0` → Not readmitted
* `1` → Readmitted

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## 🔄 Machine Learning Workflow

The general workflow followed in these case studies is:

```text
Data Collection
      ↓
Data Exploration
      ↓
Data Cleaning
      ↓
Feature & Target Selection
      ↓
Train-Test Split
      ↓
Data Preprocessing
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Result Comparison
```

## 🤖 Models

The main model used in `Case_Study1.ipynb` is:

### Logistic Regression

A classification algorithm used to predict the binary target variable.

### Logistic Regression with L2 Regularization

L2 regularization is used to control model complexity by penalizing large model coefficients.

## 📈 Evaluation Metrics

The models are evaluated using:

* **Accuracy**
* **AUC (Area Under the ROC Curve)**
* **ROC Curve**

These metrics help evaluate the classification performance of the models.

## ▶️ How to Run

1. Download or clone this repository.
2. Make sure all files are present in the same folder.
3. Open either `.ipynb` file using Jupyter Notebook or Google Colab.
4. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

5. Run the notebook cells sequentially.

If the dataset is in the same folder as the notebook, use:

```python
df = pd.read_csv("diabetic_data.csv")
```

## 🎯 Objective

The objective of these case studies is to build a strong understanding of the **Machine Learning workflow**, from data preprocessing to model training and evaluation.

## 👨‍💻 Author

**Yash Verma**

B.Tech CSE (AI & ML)
KIET Group of Institutions
