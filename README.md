# Job Salary Prediction - Machine Learning Assignment

This project is focused on exploratory data analysis, data preprocessing, classification and regression on a job salary prediction dataset.

The main goal of the project is to analyze employee-related data and build models capable of predicting:

* **Vacation category** - multiclass classification task
* **Salary** - regression task

The project follows a complete classical Machine Learning workflow, from understanding the dataset to comparing multiple models and evaluating their performance.

## Dataset

The dataset contains information about employees and job-related attributes.

Main attributes:

* `job_title` - employee job title
* `experience_years` - years of experience
* `education_level` - highest education level
* `skills_count` - number of skills
* `industry` - industry field
* `company_size` - company size
* `remote_work` - remote work availability
* `certifications` - number of certifications
* `location` - work location
* `vacation` - vacation category
* `salary` - employee salary

Prediction targets:

* `vacation` for classification
* `salary` for regression

The dataset is split into:

* training set
* validation set
* test set

## Project Objectives

The assignment covers the following main stages:

1. Exploratory Data Analysis
2. Data preprocessing
3. Classification model training
4. Regression model training
5. Model evaluation and comparison
6. Experiment logging and interpretation

## Exploratory Data Analysis

The EDA part focuses on understanding the structure and distribution of the data.

The analysis includes:

* identifying numerical and categorical attributes
* checking missing values
* analyzing value distributions
* detecting potential outliers
* studying class balance for the classification target
* analyzing correlations between attributes
* visualizing numerical features using boxplots
* visualizing categorical features using histograms and bar plots

This step helped identify how the dataset should be processed before applying Machine Learning algorithms.

## Data Preprocessing

The preprocessing pipeline includes several steps needed before training the models:

* handling missing values using imputation
* identifying and treating outliers
* encoding categorical variables
* scaling numerical features
* separating features from classification and regression targets
* preparing train and validation datasets

Categorical variables were transformed into numerical representations so that they could be used by classical Machine Learning algorithms.

Numerical features were standardized or scaled where needed, especially for models sensitive to feature scale.

## Classification Task

The classification task predicts the `vacation` category.

Target classes:

* `No Vacation`
* `Small`
* `Medium`
* `Large`

The classification workflow includes:

* creating a baseline model
* training a Decision Tree classifier
* experimenting with hyperparameters
* comparing multiple classification models
* evaluating models using accuracy, precision, recall and F1-score
* analyzing the confusion matrix

Possible models used:

* Decision Tree Classifier
* Logistic Regression
* Random Forest Classifier
* other classical Machine Learning models

## Regression Task

The regression task predicts the `salary` value.

The regression workflow includes:

* creating a Linear Regression baseline
* applying regularized regression models
* experimenting with regularization strength
* comparing multiple regression models
* evaluating models using MAE, MSE, RMSE and R² score
* analyzing training and validation error curves

Possible models used:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* other classical regression models

## Evaluation

The models are evaluated separately for classification and regression.

### Classification Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

### Regression Metrics

* Mean Absolute Error
* Mean Squared Error
* Root Mean Squared Error
* R² score

The final results are compared in tables in order to highlight the best-performing models and the effect of different preprocessing steps and hyperparameters.

## Project Structure

```bash
.
├── data/
│   ├── train.csv
│   ├── val.csv
│   └── test.csv
│
├── notebooks/
│   └── machine_learning_assignment.ipynb
│
├── reports/
│   └── report.pdf
│
├── outputs/
│   ├── figures/
│   └── submissions/
│
├── src/
│   ├── preprocessing.py
│   ├── classification.py
│   ├── regression.py
│   └── evaluation.py
│
├── requirements.txt
└── README.md
```

The exact structure may vary depending on the final implementation.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook


## Results

The project compares multiple models for both tasks.

### Best Classification Model

| Model               | Accuracy | Precision | Recall | F1-score |
| ------------------- | -------: | --------: | -----: | -------: |
| Decision Tree       |      TBD |       TBD |    TBD |      TBD |
| Logistic Regression |      TBD |       TBD |    TBD |      TBD |
| Random Forest       |      TBD |       TBD |    TBD |      TBD |

### Best Regression Model

| Model                   | MAE | MSE | RMSE |  R² |
| ----------------------- | --: | --: | ---: | --: |
| Linear Regression       | TBD | TBD |  TBD | TBD |
| Ridge Regression        | TBD | TBD |  TBD | TBD |
| Random Forest Regressor | TBD | TBD |  TBD | TBD |

The final values should be updated after running the experiments.

## Key Learnings

Through this project, I improved my understanding of:

* exploratory data analysis for tabular datasets
* handling missing values and outliers
* encoding categorical variables
* scaling numerical attributes
* training classical Machine Learning models
* classification and regression evaluation metrics
* comparing models through structured experiments
* interpreting model performance instead of only reporting scores
* documenting Machine Learning experiments clearly

## Author

**Mihai-Ionuț Păunescu**
