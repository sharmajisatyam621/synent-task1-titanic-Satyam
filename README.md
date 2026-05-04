# 🚢 Titanic Dataset - Data Cleaning Project

## 📌 Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset to make it suitable for analysis and machine learning.

---

## 🎯 Objectives

* Handle missing values
* Remove duplicate records
* Convert data types
* Rename columns for clarity
* Prepare a clean dataset for further analysis

---

## 📂 Dataset Description

The dataset contains passenger details such as:

* Passenger ID
* Name
* Age
* Gender
* Passenger Class
* Fare
* Embarked Port
* Survival Status

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas

---

## 🔍 Data Cleaning Steps

### 1. Handling Missing Values

* Filled missing **Age** with median
* Filled missing **Embarked** with mode
* Dropped **Cabin** column due to excessive missing values

---

### 2. Removing Duplicates

* Removed duplicate rows to maintain data consistency

---

### 3. Data Type Conversion

* Converted categorical columns:

  * Survived → Category
  * Passenger Class → Category

---

### 4. Renaming Columns

* Improved column names for better readability

---

## 📊 Output

* Cleaned dataset saved as:
  👉 `cleaned_titanic.csv`

---

## 🧠 Key Benefits

* Improved data quality
* Better analysis accuracy
* Ready for machine learning models

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install pandas
```

2. Run the script:

```bash
python titanic_cleaning.py
```

---

## 👤 Author

**Satyam Sharma**

---
