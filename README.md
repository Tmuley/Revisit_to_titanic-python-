# Titanic Dataset Analysis

## Problem Statement

The Titanic Dataset Analysis project aims to extract meaningful insights about passengers aboard the Titanic. It provides information on survival rates, passenger demographics, and other important characteristics. Additionally, the project focuses on handling missing data and preparing the dataset for advanced analytics or machine learning applications.

---

## Steps Followed

### Step 1: Data Loading
- Imported the Titanic dataset (`Titanic.csv`) into a Pandas DataFrame using Python.

### Step 2: Data Exploration
- Displayed key information:
  - Dataset dimensions: `df.shape`
  - Initial and final rows: `df.head()` and `df.tail()`
  - Summary statistics: `df.describe()`
  - Dataset information: `df.info`

### Step 3: Distribution Analysis
- Analyzed distributions of key columns:
  - Survival count: `df.Survived.value_counts()`
  - Passenger class count: `df.Pclass.value_counts()`
  - Gender count: `df.Sex.value_counts()`

### Step 4: Handling Missing Data
- Identified missing values using `df.isnull().sum()`.
- Handled missing data:
  - Filled missing values in the `Cabin` column with `"unknown"`.
  - Filled missing values in the `Age` column with `"unknown"`.
- Dropped the `Embarked` column as it was irrelevant.

### Step 5: Dataset Validation
- Verified that missing values were handled appropriately.
- Ensured the dataset shape after cleaning was accurate.

---

## Insights

### [1] Passenger Survival
- Survival rate: **342/891 survived**.

### [2] Missing Values
- Missing data was found and addressed in the following columns:
  - **Age**: Missing values filled with `"unknown"`.
  - **Cabin**: Missing values filled with `"unknown"`.

### [3] Class Distribution
- Analyzed how passengers were spread across the Titanic's classes (1st, 2nd, 3rd).

### [4] Gender Distribution
- Highlighted counts of male and female passengers.

---

## How to Run the Project

### Prerequisites
- **Python 3.7 or higher**.
- Install the Pandas library:  
  ```bash
  pip install pandas
## Execution Steps
Follow these steps to run the project:
-Clone the Repository
Clone this GitHub repository to your local machine using the following command:


-Navigate to the Project Directory
Move into the project directory:
--bash
  cd titanic-dataset-analysis
-Place the Dataset
Add the Titanic.csv dataset file to the project directory. Ensure the file is named correctly.
-Run the Script
-View Results

  
