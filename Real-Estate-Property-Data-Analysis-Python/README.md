# Real Estate Property Data Analysis Using Python

A Python practice project focused on learning and applying Python
for data analysis using a real estate property dataset.

## Project Overview

This project starts with the fundamentals of Python and gradually
moves into data analysis using NumPy and Pandas.

The main goal is to build practical Python skills by working with
a real-world-style real estate dataset.

## Python Introduction

Python is a popular programming language used for data analysis,
automation, web development, artificial intelligence, and machine learning.

In this project, Python fundamentals are practiced before moving
into data analysis libraries.

Topics include:

- Variables
- Data types
- Lists
- Tuples
- Dictionaries
- Conditional statements
- Loops
- Functions
- Basic Python operations

## NumPy

NumPy (Numerical Python) is a Python library used for numerical
computing and working with arrays.

It is useful for performing fast mathematical and numerical
operations on data.

Topics practiced include:

- Creating NumPy arrays
- Array indexing
- Array slicing
- Array shape
- Mathematical operations
- Statistical functions
- Working with multidimensional arrays

Example:

```python
import numpy as np

numbers = np.array([10, 20, 30, 40, 50])

print(numbers)
print(numbers.mean())
print(numbers.max())
print(numbers.min())


## Pandas

Pandas is a powerful Python library used for data manipulation,
data analysis, and working with structured datasets.

It provides two main data structures:

- **Series**: A one-dimensional labeled data structure.
- **DataFrame**: A two-dimensional table with rows and columns,
  similar to an Excel spreadsheet.

In this project, Pandas is mainly used to work with the real estate
property dataset. It allows the dataset to be loaded from Excel,
inspected, cleaned, filtered, sorted, and analyzed.

### Why Pandas is Used

Pandas makes it easier to:

- Load datasets from Excel and other file formats
- View and understand data
- Select specific columns and rows
- Filter records based on conditions
- Sort data
- Detect and handle missing values
- Remove duplicate records
- Clean inconsistent data
- Calculate statistics
- Group and summarize data
- Prepare data for visualization

### Important Pandas Functions

Some of the Pandas functions practiced in this project include:

```python
data.head()
data.tail()
data.sample()
data.shape
data.columns
data.dtypes
data.info()
data.describe()
