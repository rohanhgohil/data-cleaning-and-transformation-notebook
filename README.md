# Data Cleaning and Transformation with Pandas

This repository contains a Python script that demonstrates various data cleaning and transformation techniques using the Pandas library. The script utilizes the famous Titanic dataset in CSV format to perform the operations. Below are the main data cleaning and transformation tasks covered in the script:

### 1. Removing Columns or Rows:
- Loading the Titanic dataset into a Pandas DataFrame.
- Removing specific columns ("SibSp", "Parch", "Ticket") from the DataFrame.
- Removing the first 20 rows from the DataFrame.

### 2. Removing Duplicate Rows:
- Loading the Titanic dataset into a Pandas DataFrame.
- Adding duplicated rows from the first and second rows using a for-loop and the loc method.
- Identifing and print the duplicated rows in the DataFrame.
- Removing all duplicated rows while keeping the first occurrence of each duplicated row.

### 3. Renaming Column Labels:
- Loading the Titanic dataset into a Pandas DataFrame.
- Renaming specific columns ("Name" to "Full_Name", "Fare" to "Ticket_Price").
- Changing all column labels to new labels provided in a list.

### 4. Dropping Missing Values:
- Loading the Titanic dataset into a Pandas DataFrame.
- Checking the number of missing values in each column.
- Removing the "Cabin" column with many missing values.
- Dropping all rows with missing values.

### 5. Filling-in Missing Values:
- Loading the Titanic dataset into a Pandas DataFrame.
- Filling missing values in the "Age" column with the average age.
- Filling missing values in the "Embarked" and "Cabin" columns with the text "missing."

### 6. Creating Dummy Variables:
- Loading the Titanic dataset into a Pandas DataFrame.
- Removing certain columns ("Pclass", "SibSp", "Parch", "Ticket", "Cabin") from the DataFrame.
- Dropping rows with missing values in the "Embarked" column.
- Creating dummy variables for the "Embarked" column and concatenate them with the DataFrame.

### 7. Exporting Pandas DataFrames:
- Saving the final DataFrame into a CSV file called "output.csv" without including the index row numbers.
