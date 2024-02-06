# Titanic EDA Project

This repository contains an Exploratory Data Analysis (EDA) project on the Titanic dataset. The analysis explores various aspects of the dataset to gain insights into factors influencing the survival of passengers on the Titanic.


### Data Dictionary

| Feature      | Definition                                                  | Key                                               |
| ------------ | ------------------------------------------------------------ | ------------------------------------------------- |
| PassengerId  | Unique ID of the passenger                                   |                                                   |
| Survived     | Survival                                                    | 0 = No, 1 = Yes                                   |
| Pclass       | Ticket class                                                | 1 = 1st, 2 = 2nd, 3 = 3rd                         |
| Name         | Name of the passenger                                       |                                                   |
| Sex          | Sex                                                        |                                                   |
| Age          | Age in years                                                |                                                   |
| SibSp        | # of siblings / spouses aboard the Titanic                 |                                                   |
| Parch        | # of parents / children aboard the Titanic                 |                                                   |
| Ticket       | Ticket number                                               |                                                   |
| Fare         | Passenger fare                                              |                                                   |
| Cabin        | Cabin number                                                |                                                   |
| Embarked     | Port of Embarkation                                         | C = Cherbourg, Q = Queenstown, S = Southampton     |


- `Pclass`: A proxy for socio-economic status (SES)
  - 1st = Upper
  - 2nd = Middle
  - 3rd = Lower

- `Age`: Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5.

- `SibSp`: Sibling/Spouse indicates the number of siblings, spouses, step-siblings, or step-spouses aboard.

- `Parch`: Parent/Child indicates the number of parents, children, step-parents, or step-children aboard.

## Project Structure

- **Titanic_EDA.ipynb:** Jupyter Notebook containing the EDA code and analysis.
- **titanic.csv:** Dataset file (downloaded from Kaggle).

## Exploratory Data Analysis

The EDA includes the following steps:

1. Data Cleaning: Handling duplicates and missing values.
2. Feature Engineering: Creating new features like `family_size`, `age_group`, and `fare_group`.
3. Univariate Analysis: Analyzing individual features.
4. Bivariate Analysis: Exploring relationships between pairs of features.
5. Multivariate Analysis: Examining interactions between multiple features.

## Results and Insights

The analysis reveals key insights such as the influence of passenger class, gender, age, and family size on survival rates. Notable findings include higher survival rates for females, passengers in higher classes, and those with smaller family sizes.

