# Titanic Survival Prediction

## Task Objective

Develop a machine learning model that predicts whether a passenger survived the Titanic disaster based on features like age, gender, ticket class, fare, etc.

## Dataset

- File used: `tested.csv`

## Project Steps

1. **Data Preprocessing:**

   - Dropped irrelevant columns: `PassengerId`, `Name`, `Ticket`, and `Cabin`.
   - Filled missing values in `Age` and `Fare` using the median.
   - Encoded categorical variables (`Sex` and `Embarked`) using Label Encoding.
   - Normalized numerical features (`Age`, `Fare`, `SibSp`, `Parch`) using StandardScaler.

2. **Model Building:**

   - Used Random Forest Classifier for survival prediction.

3. **Model Evaluation:**

   - Evaluated model performance using:
     - Accuracy
     - Precision
     - Recall
     - F1-Score

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
```

2. Navigate to the project directory:

```bash
cd titanic-survival-prediction
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook Titanic_Survival_Prediction.ipynb
```

5. Run the notebook cells to preprocess the data, build, and evaluate the model.

## Project Structure

```
├── Titanic_Survival_Prediction.ipynb
├── tested.csv
├── README.md
└── requirements.txt
```

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- jupyter

## Conclusion

This project successfully builds a Random Forest model to predict survival on the Titanic dataset. With proper preprocessing and evaluation, the model achieves decent predictive performance.

