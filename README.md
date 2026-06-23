# Data Analyzer and Transformer Program 📊

## Project Overview

The **Data Analyzer and Transformer Program** is a Python-based project developed using **Jupyter Notebook**.

This project demonstrates the use of Python functions and data manipulation techniques to analyze and transform numerical datasets.

The program uses various Python concepts including:

- Built-in functions
- User-defined functions (UDF)
- `*args` and `**kwargs`
- Function documentation (`__doc__`)
- Recursion
- Lambda functions
- Global variables
- Multiple return values
- List operations and sorting


---

## Objective

The objective of this project is to create a menu-driven data analyzer that allows users to perform different operations on a 1D numerical list.

The user can:

- Enter dataset values
- Display basic statistics
- Calculate factorial using recursion
- Filter data using lambda functions
- Sort data
- Display multiple dataset statistics


---

# Features 🚀

## 1. Input Data

The user can enter numerical values manually.

Example:

```
Enter numbers separated by space:
34 12 56 78 43
```

The input values are converted into a list using:

```python
list(map(int, values.split()))
```


---

## 2. Display Data Summary

The program uses Python built-in functions to display basic statistics.

Built-in functions used:

- `len()`
- `sum()`
- `min()`
- `max()`


Example Output:

```
Length: 5
Minimum: 12
Maximum: 78
Sum: 223
Average: 44.6
```


---

# Concepts Implemented


## 1. User Defined Functions (UDF)

The project uses custom functions to perform different operations.

Examples:

```python
def average(numbers):
```

Functions are created for:

- Average calculation
- Data filtering
- Statistics calculation
- Factorial calculation


---

## 2. Built-in Functions

Python built-in functions are used for analyzing data.

Examples:

```python
len(data)

sum(data)

min(data)

max(data)
```


---

## 3. *args

The project demonstrates the use of `*args` to accept multiple values.

Example:

```python
def show_values(*args):
```

It allows a function to accept any number of arguments.


---

## 4. **kwargs

The project uses `**kwargs` to display dataset summary information.

Example:

```python
def show_summary(**kwargs):
```

It stores data in key-value format.

Example:

```
Total Values : 5
Average : 45.2
```


---

## 5. Function Documentation (__doc__)

Each function contains a documentation string describing its purpose.

Example:

```python
"""Calculate average of numbers"""
```

This improves code readability and understanding.


---

## 6. Recursion

A recursive function is implemented to calculate factorial.

Example:

```python
def factorial(n):
```

The function repeatedly calls itself until the base condition is reached.

Example:

```
Factorial of 5 = 120
```


---

## 7. Lambda Function

Lambda functions are used for filtering dataset values.

Example:

```python
lambda x:x >= limit
```

The program filters values based on the threshold entered by the user.

Example:

Input:

```
Threshold: 50
```

Output:

```
[56, 78, 90]
```


---

## 8. Global Keyword

A global variable is used to store dataset summary information.

Example:

```python
global summary
```

The summary can be accessed and modified by different functions.


---

## 9. Returning Multiple Values

A function returns multiple statistics of the dataset.

Example:

```python
return min(numbers), max(numbers), sum(numbers), average(numbers)
```

It returns:

- Minimum value
- Maximum value
- Total sum
- Average value


---

## 10. Sorting Data

The program demonstrates sorting using list methods.


### Ascending Order

```python
data.sort()
```


### Descending Order

```python
data.sort(reverse=True)
```


---

# Menu Options

The program provides the following options:

```
1. Enter Data
2. Display Summary
3. Factorial
4. Filter Data
5. Sort Data
6. Statistics
7. Exit
```


---

# Technologies Used

- Python 3
- Jupyter Notebook


---

# How to Run the Project

### Step 1: Install Jupyter Notebook

```
pip install notebook
```


### Step 2: Start Jupyter Notebook

```
jupyter notebook
```


### Step 3: Open the project file

```
Project_4.ipynb
```


### Step 4: Run all cells


---

# Project Structure

```
Data-Analyzer-Transformer/

│
├── Data_Analyzer_Transformer.ipynb
│
└── README.md
```


---

# Learning Outcomes

After completing this project, you will understand:

- How to create and use functions in Python
- Working with lists and collections
- Using lambda expressions
- Understanding recursion
- Using global variables
- Returning multiple values
- Applying Python built-in functions
- Creating menu-driven Python applications


---

## Author

**Maahroof Munshi**


